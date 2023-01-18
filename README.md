# Becoming KCNA Certified

<a href="https://www.packtpub.com/product/becoming-kcna-certified/9781804613399?utm_source=github&utm_medium=repository&utm_campaign=9781804613399"><img src="https://static.packt-cdn.com/products/9781804613399/cover/smaller" alt="" height="256px" align="right"></a>

This is the code repository for [Becoming KCNA Certified](https://www.packtpub.com/product/becoming-kcna-certified/9781804613399?utm_source=github&utm_medium=repository&utm_campaign=9781804613399), published by Packt.

**Build a strong foundation in cloud native and Kubernetes and pass the KCNA exam with ease**

## What is this book about?
The job market related to the cloud and cloud-native technologies is both growing and becoming increasingly competitive, making certifications like KCNA a great way to stand out from the crowd and learn about the latest advancements in cloud technologies.

This book covers the following exciting features:
* Get to grips with Cloud Native Computing Foundation (CNCF) and its projects
* Build, configure, and run containers with Docker
* Bootstrap minimal Kubernetes clusters for learning
* Manage and encrypt container traffic with Service Mesh
* Deploy, configure, and update applications on Kubernetes
* Control and connect the applications that run on Kubernetes
* Manage storage and provide observability on Kubernetes
* Automate software development with CI/CD and GitOps

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1804613398) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter3.

The code will look like the following:
```
apiVersion: v1
kind: PersistentVolumeClaim
metadata:
  name: kcna-pv-claim
spec:
  storageClassName: standard
  accessModes:
    - ReadWriteOnce
  resources:
    requests:
      storage: 3Gi
```

**Following is what you need for this book:**
This book is for DevOps engineers, system administrators, developers, fresh IT graduates, or anyone interested in cloud native architecture, applications, and technologies. Those with relevant work experience looking to upskill themselves in order to manage their applications with Kubernetes in a better way will also find this book helpful. Familiarity with IT fundamentals, networks, and command line interface (CLI) is required, but no prior knowledge of Kubernetes, docker, or cloud services is needed to get started with this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-13).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-13 | Kubernetes | Windows, Mac OS X, and Linux (MacOs or Linux recommended) |
| 1-13 | minikube | Windows, Mac OS X, and Linux (MacOs or Linux recommended) |
| 1-13 | Docker | Windows, Mac OS X, and Linux (MacOs or Linux recommended) |
| 1-13 | Prometheus | Windows, Mac OS X, and Linux (MacOs or Linux recommended) |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://packt.link/OnZI3).

### Related products
* The Kubernetes Bible [[Packt]](https://www.packtpub.com/product/the-kubernetes-bible/9781838827694?utm_source=github&utm_medium=repository&utm_campaign=9781838827694) [[Amazon]](https://www.amazon.com/dp/1838827692)

* Gaining some basic understanding of the Linux shell  [[Packt]](https://www.packtpub.com/product/certified-kubernetes-administrator-cka-exam-guide/9781803238265?utm_source=github&utm_medium=repository&utm_campaign=9781803238265) [[Amazon]](https://www.amazon.com/dp/1803238267)

## Get to Know the Author
**Dmitry Galkin**
is a cloud expert and a founder at Cloudification. For 12+ years he has been working with cloud technologies, cloud native solutions, DevOps, infrastructure, and service automation domains in a variety of roles. He has consulted international enterprises and supported small startups, mentored students, and developed IT certification programs for non-profit organizations as a subject matter expert.
Dmitry is an open-source contributor, and he holds more than 10 professional certifications including all 4x Kubernetes certifications from CNCF (namely, KCNA, CKA, CKAD and CKS). He is based in Berlin and holds Master of Science degree from the University of Bremen, Germany.
