# External APIs
API's (or Application Program Interfaces) are how two pieces of code interact
with each other.

Technically, every time you define a function, method, or class you're defining
an API. These APIs are often only really useful to you in your program, but
there are many kinds of APIs that are useful to a broad variety of programs.

These can be broken up into:

1. Standard Library - Classes/Types provided to you by the language.
2. Core library - Classes/Types installed by the language, but not included by
   default. Classes like `csv` are examples of the ruby core library.
3. External libraries - Code you have to download and make available to your
   application. bcrypt, shotgun, rack, sinatra, jquery, etc. are examples of
   external libraries.
4. Services - Services you communicate with over a protocol. Twitter, Google
   Maps, Twilio, postgres, Facebook etc. are examples of external services. Many
   times people will write libraries to make interacting with a service easier.
   `pg`, `bundler`, `omniauth`, and `octokit` are examples of libraries written
   to make interacting with a service easier.

## :+1:
1. I can identify whether a library I'm using is provided in the languages
   standard library, it's core library, or as an external library.
1. I have used a ruby library to interact with a service.
1. I have used omniauth to interact with an oauth provider.
1. I have used a javascript library to interact with a service.
1. I have tested my interaction with web-based services using the libraries test
   mode.

## :+1: :+1:
1. I have tested my interaction with web-based services by leveraging VCR or
   WebMock
1. I have used the oauth2 gem to interact with an oauth provider.
1. I have used a ruby HTTP library like Faraday to interact with HTTP based
   services without using their library.
1. I have released a library in either javascript or ruby
1. I have opened issues on libraries to report defects or suggest enhancements

## :+1: :+1: :+1:
1. I have released a library in both Javascript and Ruby
1. I've submitted pull requests to libraries to fix their defects/add
   enhancements
1. I have written a web based service that others can use for their own
   nefarious purposes.
