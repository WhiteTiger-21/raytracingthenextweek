Ray Tracing: The Next Week
====================================================================================================

![Ray Tracing: The Next Week](./RTNextWeek.jpg)

Getting the Book
-----------------
The _Ray Tracing in One Weekend_ series of books are now available to the public for free in PDF
form, along with the accompanying source code. Releases are available [directly from GitHub], or
from Eric Haine's [Real-Time Rendering] site. Alternatively, you can purchase the Kindle version of
this series from [Amazon.com]. Half of the proceeds of these sales go to [Hack the Hood], a really
neat organization.

Overview
---------
In [Ray Tracing In One Weekend], you built a simple brute force path tracer. In this installment
we’ll add textures, volumes (like fog), rectangles, instances, lights, and support for lots of
objects using a BVH. When done, you’ll have a “real” ray tracer.

A heuristic in ray tracing that many people—including me—believe, is that most optimizations
complicate the code without delivering much speedup. What I will do in this mini-book is go with the
simplest approach in each design decision I make. Check www.in1weekend.com for readings and
references to a more sophisticated approach. However, I strongly encourage you to do no premature
optimization; if it doesn’t show up high in the execution time profile, it doesn’t need optimization
until all the features are supported!

The two hardest parts of this book are the BVH and the Perlin textures. This is why the title
suggests you take a week rather than a weekend for this endeavor. But you can save those for last if
you want a weekend project. Order is not very important for the concepts presented in this book, and
without BVH and Perlin texture you will still get a Cornell Box!

## Corrections
If you spot errors or have suggested corrections, please [submit issues via GitHub].

Acknowledgments
----------------
Thanks to Becker for his many helpful comments on the draft and to Matthew Heimlich for spotting a
critical motion blur error. Thanks to Andrew Kensler, Thiago Ize, and Ingo Wald for advice on
ray-AABB tests. Thanks to David Hart and Grue Debry for help with a bunch of the details. Thanks to
Jean Buckley for editing.

日本語翻訳について
-------------
このリポジトリは、[WhiteTiger-21]が翻訳をしています。
間違いなどのお問合わせはissueや[Twitter of WhiteTiger-21]へのDMへお願いします。
なにかしらでお声をかけてくださると幸いです(おすすめのエナジードリンクの話題からAmazonのほしいものリストについて、並列化についてなど)
レイトレーシングのプログラミングを解説してくださる皆様に感謝します。
Thank you a lot to all concerned in Ray Tracing.

[Amazon.com]:                 https://amazon.com/dp/B01CO7PQ8C
[directly from GitHub]:     https://github.com/petershirley/raytracingthenextweek/releases/
[Hack the Hood]:              http://www.hackthehood.org
[Ray Tracing In One Weekend]: https://github.com/petershirley/raytracinginoneweekend/
[Real-Time Rendering]:        http://www.realtimerendering.com/#books-small-table
[submit issues via GitHub]:   https://github.com/petershirley/raytracingthenextweek/issues/
[WhiteTiger-21]:   https://github.com/WhiteTiger-21
[Twitter of WhiteTiger-21]:	https://twitter.com/WhiteTiger_21_s