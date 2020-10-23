# Tensorflow

My Projects with Tensorflow : 

<h1>Introduction</h1>
<p> One of popular Google Developer Products is Tensorflow. TensorFlow is an open source library for numerical computation and large-scale machine learning. TensorFlow bundles together a slew of machine learning and deep learning (aka neural networking) models and algorithms and makes them useful by way of a common metaphor. It uses Python to provide a convenient front-end API for building applications with the framework, while executing those applications in high-performance C++. </p>

<h1>How TensorFlow Works? </h1>
<p>TensorFlow allows developers to create dataflow graphs—structures that describe how data moves through a graph, or a series of processing nodes. Each node in the graph represents a mathematical operation, and each connection or edge between nodes is a multidimensional data array, or tensor. <br/></p>

<p>TensorFlow applications can be run on most any target that’s convenient: a local machine, a cluster in the cloud, iOS and Android devices, CPUs or GPUs.</p>
<p>TensorFlow 2.0, released in October 2019, revamped the framework in many ways based on user feedback, to make it easier to work with (e.g., by using the relatively simple Keras API for model training) and more performant. Distributed training is easier to run thanks to a new API, and support for TensorFlow Lite makes it possible to deploy models on a greater variety of platforms. However, code written for earlier versions of TensorFlow must be rewritten—sometimes only slightly, sometimes significantly—to take maximum advantage of new TensorFlow 2.0 features.</p>

<h1>Tensorflow Advantages</h1>
<p>The single biggest benefit TensorFlow provides for machine learning development is abstraction. Instead of dealing with the nitty-gritty details of implementing algorithms, or figuring out proper ways to hitch the output of one function to the input of another, the developer can focus on the overall logic of the application. TensorFlow takes care of the details behind the scenes.
<br/>
TensorFlow offers additional conveniences for developers who need to debug and gain introspection into TensorFlow apps. The eager execution mode lets you evaluate and modify each graph operation separately and transparently, instead of constructing the entire graph as a single opaque object and evaluating it all at once. </p>

<p>TensorFlow also competes with a slew of other machine learning frameworks. PyTorch, CNTK, and MXNet are three major frameworks that address many of the same needs. Below I’ve noted where they stand out and come up short against TensorFlow.
<ul>
  <li><b>PyTorch</b>, in addition to being built with Python, and has many other similarities to TensorFlow: hardware-accelerated components under the hood, a highly interactive development model that allows for design-as-you-go work, and many useful components already included. PyTorch is generally a better choice for fast development of projects that need to be up and running in a short time, but TensorFlow wins out for larger projects and more complex workflows. </li>
  <li><b>CNTK</b>, the Microsoft Cognitive Toolkit, like TensorFlow uses a graph structure to describe dataflow, but focuses most on creating deep learning neural networks. CNTK handles many neural network jobs faster, and has a broader set of APIs (Python, C++, C#, Java). But CNTK isn’t currently as easy to learn or deploy as TensorFlow.</li>
<li><b>Apache MXNet</b>, adopted by Amazon as the premier deep learning framework on AWS, can scale almost linearly across multiple GPUs and multiple machines. It also supports a broad range of language APIs—Python, C++, Scala, R, JavaScript, Julia, Perl, Go—although its native APIs aren’t as pleasant to work with as TensorFlow’s.</li>
<br/>
</ul>
<p> Taken From : https://www.infoworld.com/article/3278008/what-is-tensorflow-the-machine-learning-library-explained.html </p>
