---
layout: post

title: Data Attributes
subtitle: "How to customize the SubToMe button to fit your needs!"

author:
  name: Julien Genestoux
  link: http://ouvre-boite.com/
  image: http://www.gravatar.com/avatar/b30ce50678f0e934eaa6697425c59dd7?s=256
  bio: Co-founder, Superfeedr.
---

Last week, I met <a href="http://www.chrisvanpatten.com/">Chris</a> and we had a great discussion on how to improve SubToMe by supporting <code>data-*</code> attributes on the buttons. This is an <a href="http://www.w3.org/html/wg/drafts/html/master/#custom">HTML5 spec</a> which enables developers to embed data along with its related DOM element. This is exactly how SubtoMe should be designed as per <a href="https://github.com/superfeedr/subtome/issues/60">Chris comments</a>.

Using different feeds for **multiple buttons** has been a pretty common feature request. No later than last week, <a href="http://www.evilprofessor.co.uk/">LLoyd</a> asked for it. Even though it is possible without the data attributes, it involves a lot more Javascript and is significantly less elegant.

Now, each SubToMe button can be configured to specify what are the resources being susbcribed to, as well as the feeds. The button can also be used to include a *recommended tool* for the subscription.

Check the [publisher documentation](http://docs.subtome.com/publishers/) if you want to see how this can be setup for your buttons very easily!

