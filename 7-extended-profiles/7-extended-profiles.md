Extended Profiles: Why the Lucky Stiff
======================================

Why the Lucky Stiff, "\_why" for short, was an online persona, famous in the Ruby community.
He was well known because of his eccentric personality, prolific open source work, and
for his creation of the "[Poignant Guide to Ruby](http://mislav.uniqpath.com/poignant-guide/book/)".

The Poignant Guide became famous because it was not only one of the early introductions to Ruby,
but it came with a soundtrack, featuring [songs](http://web.archive.org/web/20070703051421/http://poignantguide.net/sdtrk/)
like "this book is made (of rabbits and lemonade)",
and was illustrated with cartoon foxes, solidifying phrases like "chunky bacon" into the Ruby argot.

He liked to [tease DHH](http://favstar.fm/users/_why__/status/1651491822), illustrated
Matz' book "[The Ruby Programming Language](http://www.amazon.com/Ruby-Programming-Language-David-Flanagan/dp/0596516177/)",
and even made some [videos](http://www.youtube.com/user/whytheluckystiff/videos?view=0&flow=grid) about Ruby.

\_Why was deeply knowledgable about the internals of Ruby, and achieved feats that are still quite
difficult. Hackety Hack, for example, was a gui programming environment like Kids Ruby.
And when you'd made your program, it had an installer that would
package it into a single executable. No need to have your friends install Ruby and libraries
to run your programs, you just gave them a single executable program.

To facilitate Hackety Hack, he needed a gui library, so he built Shoes. Unlike most solutions
that rely on cross-platform tools like the JVM, Hackety Hack had native bindings to each of the major Oses.
It came with a book, to teach it, also: "[Nobody Knows Shoes](http://cloud.github.com/downloads/shoes/shoes/nks.pdf)"
It had a straightforward DSL that brought the difficult
world of gui development in reach of the average programmer.

The difficult problems don't stop there, he wrote syck, the YAML library that was standard
in Ruby since version 1.8 (since replaced by PSYCH). And Hpricot, an XML parser
which was a staple of Ruby development until the rise of Nokogiri (to which he
[said](http://favstar.fm/users/_why__/status/2484099316)
'caller asks, "should i use hpricot or nokogiri?" if you’re NOT me: use nokogiri.
and if you’re me: well cut it out, stop being me.'

His creativity wasn't limited to comics, books, music and videos, even his code exuded this way of thinking.
For example, in [Camping](http://camping.io/), a web framework that he wrote, to make a controller you would write:

    module Nuts::Controllers
      class Index < R '/'
        def get
          Time.now.to_s
        end
      end
    end

What is that `R '/'`? R is a method that takes a route, and dynamically creates a class which
Index then inherits from.

In Hpricot, you could search a document with `doc/"#elementID"`, the document has the division
method defined on it, allowing us to use xpath style code in Ruby.

Why's existence in the Ruby community has been described as a
"[piece of performance art](http://www.tumblr.com/tagged/why%20the%20lucky%20stiff)".
In part because of he held to this persona so strongly, and in part because he was anoymous.
No one knew who he was in real life.

Then, in 2009, he disappeared. He took down his websites, cancelled his various accounts,
removed his open source work, and was simply gone. No one knew for sure why he left, only that he did.
People speculated that it was because his real identity had been discovered and published.
I suspect, though, that while that probably played a part, that a lot of it was seeing his work
fall apart. In the time before he left, I noticed this theme on several different occasions, such
as the [tweet](http://favstar.fm/users/_why__/status/3389695893) "programming is rather thankless.
you see your works become replaced by superior works in a year. unable to run at all in a few more."

His impact, though, will stay with the Ruby community for a very long time. In appreciation of his
influence, the community established [whyday](http://whyday.org/), saying '...we need to play.
If we don't occasionally break out of the mold of our "best practices," we can easily miss many
wonderful ideas, some of which can bear rich fruit (just as Camping and Hpricot led to Sinatra and Nokogiri).
On August 19, 2010, the Ruby community celebrated Whyday. We set aside that day to remember
Why's contributions to our community and culture by hacking just for the fun and joy of it.'

For me, Why was an early inspiration. I began programming in C and Ruby time in 2008,
while in school. Programming was always equated to mathematics. A powerful but humorless environment.
No thought was given to the art of the code itself, only the data structures and the algorithms.
Why showed me that code is an art. To this day, despite the 8th Light rhetoric, I still see code
as art more than craft. Programming is the ultimate paint brush, you can create the very
universe you exist within. Solve any problem you are inclined to address. Construct
"[extremely intricate mind castles](http://olabini.com/blog/2012/02/notes-on-syntax/)" from nothing.

That's not to say I take his philosophies whole cloth. I place much more value on tests than Why did.
I suspect I find more joy in a well crafted program (though I use my own standards to identify this).
But still, there is the humour, the art, the beauty, the simple joy of doing something extravagant
or absurd or just plain unexpected. Why embodied and shared the creativity of programming, something
I'm extremely fortunate to have found early in my career.

