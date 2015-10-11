docker resource list
===============
Include blogs, articles, papers, docs, or even source code.

**Index**

1. [Tutorials](#docker_tutorials)
1. [Blogs/Articles](#docker_blogs)
1. [Docker In Industry](#docker_in_industry)


<a name="docker_tutorials"></a>
# docker Tutorials

TODO


<a name="docker_blogs"></a>
# Blogs/Articles

1. [Creating containers - Part 1](http://crosbymichael.com/creating-containers-part-1.html)

  > This is part one of a series of blog posts detailing how docker creates
  containers. We will dig deep into the various pieces that are stitched
  together to see what it takes to make docker run ... awesome.

1. [Introduction to Linux namespaces - Part 1: UTS](http://blog.yadutaf.fr/2013/12/22/introduction-to-linux-namespaces-part-1-uts/)

  > Yet Another Enthusiast Blog!

1. [docker基础技术：Linux Namespace（上）](http://coolshell.cn/articles/17010.html)

  > 时下最热的技术莫过于Docker了，很多人都觉得Docker是个新技术，其实不然，
  Docker除了其编程语言用go比较新外，其实它还真不是个新东西，也就是个新瓶装旧酒
  的东西，所谓的The New “Old Stuff”。Docker和Docker衍生的东西用到了很多很酷的
  技术，我会用几篇 文章来把这些技术给大家做个介绍，希望通过这些文章大家可以
  自己打造一个山寨版的docker。

1. [Docker基础技术：Linux Namespace（下）](http://coolshell.cn/articles/17029.html)

  > 在 Docker基础技术：Linux Namespace（上篇）中我们了解了，UTD、IPC、PID、
  Mount 四个namespace，我们模仿Docker做了一个相当相当山寨的镜像。
  在这一篇中，主要想向大家介绍Linux的User和Network的Namespace。

1. [Docker基础技术：Linux CGroup](http://coolshell.cn/articles/17049.html)

  > 前面，我们介绍了Linux Namespace，但是Namespace解决的问题主要是环境隔离的问题，
  这只是虚拟化中最最基础的一步，我们还需要解决对计算机资源使用上的隔离。
  也就是说，虽然你通过Namespace把我Jail到一个特定的环境中去了，
  但是我在其中的进程使用用CPU、内存、磁盘等这些计算资源其实还是可以随心所欲的。
  所以，我们希望对进程进行资源利用上的限制或控制。这就是Linux CGroup出来了的原因。

1. [Docker基础技术：AUFS](http://coolshell.cn/articles/17061.html)

  > AUFS是一种Union File System，所谓UnionFS就是把不同物理位置的目录合并mount
  到同一个目录中。UnionFS的一个最主要的应用是，把一张CD/DVD和一个硬盘目录给
  联合 mount在一起，然后，你就可以对这个只读的CD/DVD上的文件进行修改（
  当然，修改的文件存于硬盘上的目录里）。

1. [Docker基础技术：DeviceMapper](http://coolshell.cn/articles/17200.html)

  > 在上一篇介绍AUFS的文章中，大家可以看到，Docker的分层镜像是怎么通过UnionFS
  这种文件系统做到的，但是，因为Docker首选的AUFS并不在Linux的内核主干里，
  所以，对于非Ubuntu的Linux分发包，比如CentOS，就无法使用AUFS作为Docker的
  文件系统了。于是作为第二优先级的DeviceMapper就被拿出来做分层镜像的一个实现。

1. [深入分析Docker镜像原理](http://www.csdn.net/article/2015-08-21/2825511)

  > CSDN Container微信群邀请到DaoCloud软件工程师孙宏亮，他带来了Docker
  镜像原理的深度分享，分享内容包含两个部分：1.Docker镜像的基本知识；
  2.Dockerfile、Docker镜像与Docker容器的关系。

<a name="docker_in_industry"></a>
# docker in Industry

1. [[译] Yelp是如何使用Docker的？](http://dockone.io/article/626)

  > 每天都有成千上万的人在使用Yelp的SeatMe来完成餐厅预订服务。
  这篇博客将会深入地讲解Yelp是如何使用Docker来开发并部署SeatMe系统的。

1. [微博红包：大规模Docker集群实践经验分享](http://www.infoq.com/cn/articles/large-scale-docker-cluster-practise-experience-share)

  > 每年除夕看春晚，今年除夕抢红包。在整个羊年的春节假期里，大家都在忙着抢
  各种各样的电子红包，互联网用红包的方式革新了我们的拜年方式。为此，
  InfoQ策划了“春节红包”系列文章，以期为读者剖析各大平台的红包活动背后的技术细节。
  本文为微博篇。

  > 羊年春晚Docker集群成功的为1.02亿小伙伴刷微博、抢红包提供了可靠的服务。
  本文将为大家揭开微博平台Docker集群的神秘面纱，包括集群规模，技术架构等方面情况。

1. [美团: 基于容器的自动构建](http://tech.meituan.com/autobuild.html)

  > 自动构建系统是从美团的自动部署系统发展出来的一个新功能。每当开发人员提交
  代码到仓库后，系统会自动根据开发人员定制的构建配置，启动新的Docker容器，
  在其中对源代码进行构建（build），包括编译（如Java、C++和Go）、
  预处理（如Javascript和CSS）、压缩（如图片）等操作，生成最终需要上线的程序包。

1. [暴走漫画的Docker实践](http://dockone.io/article/718?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)

  > 分享Docker在暴漫中的应用主要包括：开发环境的Service搭建，代码托管、
  持续集成、Docker镜像等若干Support服务、部分微服务以及整个数据服务系统。

1. [Segment: Rebuilding Our Infrastructure with Docker, ECS, and Terraform](https://segment.com/blog/rebuilding-our-infrastructure/)

  > `Segment` is a startup company, and raised $27 million Series B from
  Thrive, Accel, at Oct, 2015.
