
## Installation

Add this line to your application's Gemfile:

```ruby
gem 'action_mailbox_amazon_ingress', '~> 0.1.3'
```

## Configuration

### Amazon SES/SNS

Configure _SES_ to [route emails through SNS](https://docs.aws.amazon.com/ses/latest/DeveloperGuide/configure-sns-notifications.html).

If your website is hosted at https://www.example.com then configure _SNS_ to publish the _SES_ notification topic to this _HTTP_ endpoint:

https://example.com/rails/action_mailbox/amazon/inbound_emails