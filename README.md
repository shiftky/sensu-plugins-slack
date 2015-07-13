## Sensu-Plugins-slack

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-slack.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-slack)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-slack.svg)](http://badge.fury.io/rb/sensu-plugins-slack)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-slack/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-slack)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-slack/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-slack)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-slack.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-slack)
[ ![Codeship Status for sensu-plugins/sensu-plugins-slack](https://codeship.com/projects/26ebc260-e88a-0132-5df3-62885e5c211b/status?branch=master)](https://codeship.com/projects/82829)

## Functionality

## Files
 * handler-slack.rb

## Usage
```
{
  "slack": {
    "webhook_url": "webhook url",
    "channel": "#notifications-room, optional defaults to slack defined",
    "message_prefix": "optional prefix - can be used for mentions",
    "surround": "optional - can be used for bold(*), italics(_), code(`) and preformatted(```)",
    "bot_name": "optional bot name, defaults to slack defined",
    "template": "/some/path/to/template.erb",
    "fields": [
      "list",
      "of",
      "optional",
      "clientkeys",
      "to_render"
    ]
  }
}
```
## Installation

[Installation and Setup](http://sensu-plugins.io/docs/installation_instructions.html)

## Notes
