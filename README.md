# crystal-uuid

Simple translation of Robert Kieffer javascript file
http://www.broofa.com/Tools/Math.uuid.js

## Installation

Add this to your application's `shard.yml`:

```yaml
dependencies:
  crystal-uuid:
    github: qio-io/crystal-uuid
```

## Usage

```crystal
require "crystal-uuid"

puts UUID.generate
puts UUID.generate_simple
```

Just call UUID.generate_simple or UUID.generate. This library is pseudo uuid, in reality you'll need the mac address of the hardware to create a real uuid. Maybe later i could prepare the c bindings to libuuid that could be a better option in the long run.


## Contributing

1. Fork it ( https://github.com/qio-io/crystal-uuid/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [[qio-io]](https://github.com/qio-io)  - creator