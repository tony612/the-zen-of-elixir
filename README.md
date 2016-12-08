# The Zen of Elixir

Mastering Elixir is *not easy*. This project tries to collect the most inspiring
resources about Elixir. It's not about teaching the basics, it's about the most
important things that every Elixir programmer should know.

There're articles, talks etc.. covering various topics, but they can be hard to
find as Elixir beginners. That's why this project is created. *These resources are useful
and inspiring even if you don't program in Elixir (yet).*

(Check out [awesome-elixir](https://github.com/h4cc/awesome-elixir#resources)
for a list of books, tools, forums etc.. for Elixir)

## Erlang

* [The Zen of Erlang](http://ferd.ca/the-zen-of-erlang.html) （[中文翻译](http://blog.aquarhead.me/2016/09/the-zen-of-erlang)）

It's important to understand Erlang - not the syntax - if you want to be a master of Elixir.
Learn to think in *the BEAM way* by reading Fred's great article.

* [Tail Call Optimization in Elixir & Erlang – not as efficient and important as you probably think](https://pragtob.wordpress.com/2016/06/16/tail-call-optimization-in-elixir-erlang-not-as-efficient-and-important-as-you-probably-think/)

Every book about FP have a section on tail recursion, but should we really always program in this style? More importantly, when in doubt, benchmark it!

* [Thinking in Erlang](https://web.archive.org/web/20070212210331/http://chuffyrodents.org/erlang.pdf)

A high level but useful survey of Erlang and its programming model for procedural programmers.

## Elixir

* [Beyond Functional Programming with Elixir and Erlang](http://blog.plataformatec.com.br/2016/05/beyond-functional-programming-with-elixir-and-erlang/)

Erlang and Elixir are considered as functional languages. However, *it's not a goal*.
So what is the goal of Elixir? And how FP contributes to it? Read this to find out.

* [Comparing Elixir and Erlang variables](http://blog.plataformatec.com.br/2016/01/comparing-elixir-and-erlang-variables/)

It can be confusing to understand rebinding of immutable variables in Elixir.
Let José explain this for you :)

* [Elixir in times of microservices](http://blog.plataformatec.com.br/2015/06/elixir-in-times-of-microservices/)

Elixir excels at scalability and maintainability, but how to achieve this?
You should consider **umbrella projects** first for your great projects.

* [Mocks and explicit contracts](http://blog.plataformatec.com.br/2015/10/mocks-and-explicit-contracts/)

Elixir is dynamically typed, so tests are important. It's functional, so it's very
different to write tests. Forget what you know and learn from this great post.

* Elixir and IO Lists [Part 1](https://www.bignerdranch.com/blog/elixir-and-io-lists-part-1-building-output-efficiently/), [Part 2](https://www.bignerdranch.com/blog/elixir-and-io-lists-part-2-io-lists-in-phoenix/), [Talk](https://www.youtube.com/watch?v=zZxBL-lV9uA)

Be it rendering HTTP response, querying database or even writing to a file, what you actually operate on are *bytes*. All your messages passed around in distributed Erlang clusters are bytes too. How can we send bytes more efficiently? Do we really need to build the entire response or query as one whole thing before sending it? Check out this excellent series to learn the "secrets" of sending bytes.

## Phoenix

*We believe Elixir should not be limited to Phoenix, but still keep this section considering its popularity.*

* [Phoenix Is Not Your Application](http://www.elixirconf.eu/elixirconf2016/lance-halvorsen)
and [the discussion on elixirforum](https://elixirforum.com/t/phoenix-is-not-your-application-questions/735)

Phoenix is just an [application](http://elixir-lang.org/docs/stable/elixir/Application.html)
like other applications. So learn to think of Phoenix in this way from this talk.

# Contributing

Please provide a link and a summary describing why it's important knowledge for
Elixir programmers.
