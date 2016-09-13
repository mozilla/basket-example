# Basket Example Code

Sample code for newsletter subscriptions via basket.mozilla.org. See it in action at https://mozilla.github.io/basket-example/.

## Tips

* Use "success@example.com" as the email to have the request return successfully but not actually record a subscription,
  and "failure@example.com" to always return failure.
* You may also send "country" and "lang" parameters to indicate the user's country and language respectively
  (see the [forms on mozilla.org](https://www.mozilla.org/en-US/newsletter/) for examples)
* You may also send a "fmt" parameter with the value "H" or "T" for "HTML" and "Text", which will indicate the user's
  preferred email format. HTML is the default.
