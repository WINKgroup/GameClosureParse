# Game Closure Native Inspector

## Overview

The GameClosure Parse SDK is a sdk for [Parse](https://parse.com/):


## How it Works

GameClosure Parse SDK use the javascript sdk v1.2.18 of Parse

## Usage

You can find all use of Parse object at [Parse js API](https://parse.com/docs/js_guide)

example:
~~~
import parse.Parse as Parse;

...

Parse.initialize("AppId", "AppKey");
        
var TestObject = Parse.Object.extend("TestObject");
var testObject = new TestObject();
testObject.save({foo: "bar"}).then(function(object) {
	console.log("yay! it worked");
});
~~~
