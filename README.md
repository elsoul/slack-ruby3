<p align="center">
  <a aria-label="Ruby logo" href="https://el-soul.com">
    <img src="https://badgen.net/badge/icon/Made%20by%20ELSOUL?icon=ruby&label&color=black&labelColor=black">
  </a>
  <br/>

  <a aria-label="Ruby Gem version" href="https://rubygems.org/gems/slack-ruby3">
    <img alt="" src="https://badgen.net/rubygems/v/slack-ruby3/latest">
  </a>
  <a aria-label="Downloads Number" href="https://rubygems.org/gems/slack-ruby3">
    <img alt="" src="https://badgen.net/rubygems/dt/slack-ruby3">
  </a>
  <a aria-label="License" href="https://github.com/elsoul/slack-ruby3/blob/master/LICENSE">
    <img alt="" src="https://badgen.net/badge/license/Apache/blue">
  </a>
</p>

## What's Slack::Ruby3 ?

Slack Notification Compatible with Ruby version 3.0.0 ~

## Installation

Add this line to your application's Gemfile:

```ruby
gem "slack-ruby3"
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install slack-ruby3

## Usage

Console

    $ slack-ruby3 $WEBHOOK_URL, $MESSAGE
    
    
 Ruby
    
```ruby
    require "slack/ruby3"
    
    Slack::Ruby3.push webhook_url: "https:/xxxxx.xxxx.xxxx.xxxx", messages: "hoi!"
```
## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org/gems/slack-ruby3).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/elsoul/slack-ruby3. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [Apache-2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

## Code of Conduct

Everyone interacting in the HotelPrice project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/elsoul/slack-ruby3/blob/master/CODE_OF_CONDUCT.md).
