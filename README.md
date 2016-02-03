# motion-scene-kit

### SceneKit stuff in RubyMotion

Some things wrapped, new stuff added, some pain removed

**This is very preliminary, I'm using it in a real app, but it's very rough at this point.**

![image](http://ir_wp.s3.amazonaws.com/wp-content/uploads/sites/11/2014/08/motion-scene-kit-sample.jpg)

Works in both OS X and iOS. You need to target iOS 8.0 or higher (8 is when Apple added SceneKit to iOS)

motion-scene-kit is a research project of [Infinite Red](http://infinite.red), a web and mobile development company based in Portland, OR and San Francisco, CA.

## Installation



Add this line to your application's Gemfile:

```
gem 'motion-scene-kit', :git => 'https://github.com/infinitered/motion-scene-kit'
```

And then execute:

```
$ bundle
```

## Requires

* Geomotion. You can use Geomotion's nice CATransform3D stuff

## Uses Frameworks

This gem will automatically link the following frameworks into your app: `SceneKit`, `QuartzCore`, `GLKit`, & `AVFoundation`

## Sample app

This repo has its own OSX sample app. It does not get included in the gem. Clone this repo, then bundle, then rake.

## Usage

TODO: 

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
