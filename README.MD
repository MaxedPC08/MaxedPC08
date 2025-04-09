Hello! I am Max, a highschool student with a love for learning of all sorts - machine, deep, or academic. I generally work on python machine learning projects, though I do know numerous other languages.
I am currently learning all that I can about large language models and I hope to crack into MMMs soon if I can. I am limited by my singular RTX 3060 GPU, but I consider it a blessing in disguise, as it teaches / forces me to write memory optimized code. I do use AI to code, but only to handle trivial tasks that I am sure I know how to do. I enjoy mechanical engineering, and have really found my place doing robotics, which feels like a nice mix of CS and mechanical engineering. I am always open to new opportunities, so reach out!

# Major Projects:
## [Astrolabe:](https://github.com/MaxedPC08/Astrolabe)
I created a full vision processing library for FIRST Robotics Competition teams. It can be installed on any linux coprocessor (Raspberry PI, Orange PI, etc.) and has a corresponding user interface. It is capable of handling multiple camreras at once, parallel requests, AprliTag detection, and color based object detection. On a Raspberry Pi 3B+, Astrolabe achieved about 40 fps with two cameras at 480p and 100 fps with a Raspberry Pi 5.

## [Adalpha:](https://github.com/MaxedPC08/Adalpha)
Adalpha was my personal spin on the Adam optimizer for machine learning. Essentially, it calculates the speed at which the model is learning and attempts to adjust the rate at which weights are changed to improve performance. Additiaionally, it "kickstarts" weights that are barely changing in an attempt to find more optimal values. Ultimately, it worked about as well as Adam, but was more forgiving with poorly choosen learning rates and models that often plateau.

## [TreeNet:](https://github.com/MaxedPC08/TreeNet)
***Still in a testing phase***

I created TreeNet as a cross between sequential AI models and Mixture of experts. Essentially, the model has some number of input nodes, from which the gate selects. Each node feeds its output to its parent, and every node, aside from the input nodes, has two children. For a model with *n* experts, a tree network only has 2n-1 nodes, where the same model in a traditional mixture of experts would have n*log_2(n) nodes. This significantly reduces space and time complexity, and, in theory, reduces the amount of training required, as there are fewer late-model layers that create the output (for example, layers in large language models that translate internal values back into words should be pretty universal, so reducing the number of them that need training is a good way to optimize the training process).

## [FYRE2025:](https://github.com/FYRE5480/FYRE2025)
***This was a team effort. Check repository for other contributors.***

This year, I was on both the mechanical and the programming team on my FRC robotics team, FYRE 5480. This is the repository for our full robot code. I worked mostly on vision processing and human control, but I also helped develop our swerve drive software.

# Minor Projects
## [Quick Browse and Notes](https://github.com/MaxedPC08/QuickBrowseAndNotes)
This is a simple script that allows users to search the web and take notes with a single key-bind. I developed it mainly for personal use, but some friends liked it, so it is now public!

## [NetBloks](https://github.com/MaxedPC08/NetBloks)
This is my team's submission to UNR ACM's Biggest Little Hackathon. It is an app that allows users to construct AI models with block coding then run or export them with Pytorch. We had 40 hours to make it, so it is very bug-ridden, but it is still an epic project!


