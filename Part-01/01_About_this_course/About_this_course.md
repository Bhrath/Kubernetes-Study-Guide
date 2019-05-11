# Kubernetes By Example

The course takes a learn-by-doing approach so that you get acquainted with as many of the kubernetes features as quickly as possible. At it's core, Kubernetes is all about using the  `kubectl` command along with yaml files that you feed into it. That's why this course is primarily focused on how to write these yaml files and then feeding them into the `kubectl`. The hope is that you'll understand and learn kubernetes faster by seeing it in action and following along.


## Certified Kubernetes Administrator

In case you're interested, you can get certified by taking the [Certified Kubernetes Administrator](https://www.cncf.io/certification/cka/) exam. This isn't a multiple choice exam, it's actually a hands-on exam where you perform tasks on a live Kubernetes environment. And since this course is a hands-on course, it makes it a good companion guide to help you prepare for the exam.

I should point out that the [exam curriculum](https://github.com/cncf/curriculum) is regularly updated, and this course doesn't quite cover the whole curriculum. However I am planning to create further courses to cover the missing parts in upcoming courses.

In the exam you will be allowed to access all web pages under the [https://kubernetes.io/docs/](https://kubernetes.io/docs/). As well as all pages under [https://github.com/kubernetes/kubernetes](https://github.com/kubernetes/kubernetes). That's why in this course I will regularly refer to these two sources, so that you can find your around them.

## Study guide

This course comes with it's very own study guide which I strongly recommend that you clone to your workstation:

[https://github.com/Sher-Chowdhury/Kubernetes-Study-Guide](https://github.com/Sher-Chowdhury/Kubernetes-Study-Guide)

This Study guide has all the sample commands and files that I'll be using in course. This will save you from having to manually type out everything I do. I've broken this course down into number of easier-to-digest parts. 

This study guide is constantly evolving and is being regularly updated with improvements and new content. Also if you have any suggestions about making changes then please raise an issue or submit a pull request.


## What's not covered

- Various ways of installing Kubernetes, we only show the minikube approach.
- Other tools that are also used in the wider Kubernetes ecosystem, e.g. [helm](https://helm.sh/), [traefik](https://traefik.io/),...etc. This course is going to be long enough as it is just with me just covering Kubernetes on it own!
- Kubernetes Administration, e.g. updating existing Kubernetes install to a newer version. 
- Cloud platform specific technologies, such as [AWS EKS](https://aws.amazon.com/eks/). This course is going to be cloud agnostic, meaning that what we'll cover should work on most, if not all cloud platforms, whether it is AWS, Azure, GKE...etc.

I'm hoping to cover some of these areas in a future upcoming courses.

## Notations and where to find help

Throughout this course we'll be using the kubectl command. kubectl is the main command used for performing day-to-day kubernetes work. kubectl has a lot of built in reference docs. That includes lots of man pages:

```bash
man kubectl<tab><tab>
```

Also you can access a lot more info by running:

```bash
kubectl explain xxxxx
```

Where 'xxxxx', is set to something like 'pod.spec'.

The output of some commands are quite long, on those occasions we'll only show an extract using 3-dot notation, and truncate out the rest:

```text
$ kubectl describe pods
...
output of interest
...
```

## Bookmarks

[https://towardsdatascience.com/key-kubernetes-concepts-62939f4bc08e?sk=d46386ce56c00701dbf41aa8d308a14d](https://towardsdatascience.com/key-kubernetes-concepts-62939f4bc08e?sk=d46386ce56c00701dbf41aa8d308a14d)

[https://github.com/ramitsurana/awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes)

[https://kubectl.docs.kubernetes.io/pages/kubectl_book/getting_started.html](https://kubectl.docs.kubernetes.io/pages/kubectl_book/getting_started.html)