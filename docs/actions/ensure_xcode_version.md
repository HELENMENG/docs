<!--
This file is auto-generated and will be re-generated every time the docs are updated.
To modify it, go to its source at https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/ensure_xcode_version.rb
-->

# ensure_xcode_version


Ensure the right version of Xcode is used




> If building your app requires a specific version of Xcode, you can invoke this command before using gym.<br>For example, to ensure that a beta version of Xcode is not accidentally selected to build, which would make uploading to TestFlight fail.<br>You can either manually provide a specific version using `version: ` or you make use of the `.xcode-version` file.


ensure_xcode_version ||
---|---
Supported platforms | ios, mac
Author | @JaviSoto, @KrauseFx



## 1 Example

```ruby
ensure_xcode_version(version: "7.2")
```





## Parameters

Key | Description | Default
----|-------------|--------
  `version` | Xcode version to verify that is selected | 

<em id="parameters-legend-dynamic">* = default value is dependent on the user's system</em>


<hr />

## Documentation

To show the documentation in your terminal, run
```no-highlight
fastlane action ensure_xcode_version
```

<hr />

## CLI

It is recommended to add the above action into your `Fastfile`, however sometimes you might want to run one-offs. To do so, you can run the following command from your terminal

```no-highlight
fastlane run ensure_xcode_version
```

To pass parameters, make use of the `:` symbol, for example

```no-highlight
fastlane run ensure_xcode_version parameter1:"value1" parameter2:"value2"
```

It's important to note that the CLI supports primitive types like integers, floats, booleans, and strings. Arrays can be passed as a comma delimited string (e.g. `param:"1,2,3"`). Hashes are not currently supported.

It is recommended to add all _fastlane_ actions you use to your `Fastfile`.

<hr />

## Source code

This action, just like the rest of _fastlane_, is fully open source, <a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/ensure_xcode_version.rb" target="_blank">view the source code on GitHub</a>

<hr />

<a href="/actions/"><b>Back to actions</b></a>
