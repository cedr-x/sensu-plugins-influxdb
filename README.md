## Sensu-Plugins-influxdb

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-influxdb.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-influxdb)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-influxdb.svg)](http://badge.fury.io/rb/sensu-plugins-influxdb)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-influxdb/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-influxdb)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-influxdb/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-influxdb)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-influxdb.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-influxdb)
[![Codeship Status for sensu-plugins/sensu-plugins-influxdb](https://codeship.com/projects/94979580-cd12-0132-f567-767651b3a193/status?branch=master)](https://codeship.com/projects/76219)
## Functionality

## Files
 * bin/check-influxdb.rb
 * bin/check-influxdb-query.rb
 * bin/metrics-influxdb.rb

## Usage

**metrics-influxdb**
```
{
    "influxdb"   : {
               "server"      : "influxdb.familyguy.com",
               "port"        : "8086",
               "username"    : "root",
               "password"    : "root",
               "database"    : "stats"
     }
}
```

## Installation

[Installation and Setup](https://github.com/sensu-plugins/documentation/blob/master/user_docs/installation_instructions.md)


## Notes