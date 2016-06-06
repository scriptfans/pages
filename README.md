# Pages::Rails

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/pages/rails`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'pages-rails','2.1.4',:git => 'https://github.com/revoxltd/pages-rails.git'
```

Install from branch/tag/release
```
gem 'pages-rails', :git => "https://github.com/revoxltd/pages-rails.git", :ref => "4aded"
gem 'pages-rails', :git => "https://github.com/revoxltd/pages-rails.git", :branch => "2-3-stable"
gem 'pages-rails', :git => "https://github.com/revoxltd/pages-rails.git", :tag => "v2.3.5"
```
And then execute:

    $ bundle

Or install it yourself as:

    $ gem install pages-rails

## Usage
1. Add to your application.js
Will Include core pages.js
```
//= require pages
```

Adding other components like calendar,email etc
```
//= require pages.calendar
//= require pages.email
//= require pages.social
```

2. Add to your application.css
```
*= require pages
```

 or include rtl version
```
*= require pages.rtl
```

Include theme (dont include with pages.rtl or pages, only include the following)
```
 *= require themes/abstract
 ```