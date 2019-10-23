# IBM Application Navigator

IBM Application Navigator is a tool that extends the Kubernetes® console to provide display, inspection, understanding and expose day 2 operations of applications comprised of Kubernetes resources and existing middleware, such as WebSphere Application Server. App Navigator extends the open source [Kubernetes Application Navigator (kAppNav)](https://kappnav.io) by providing integration with WebSphere ND Cells and Liberty Collectives, enabling visibility to both existing and containerized applications.

IBM Application Navigator is designed to satisfy a need for application operators to focus on containerized applications instead of the infrastructure view that the Kubernetes platform consoles provide. This IBM design yields a superior user experience for applications that dramatically surpasses the infrastructure view. For more information about this need, which the Kubernetes Application Special Interest Group (SIG) identified, see https://github.com/kubernetes-sigs/application.

Using IBM Application Navigator, you can visually navigate to the respective components of the applications. Each component is a Kubernetes resource, such as a deployment or service resource, and has a Kind. IBM Application Navigator facilitates day 2 operations by providing action menu items by Kind. These menu items provide URLs and scriptable commands that enable you to navigate to, and operate, other tools in context for the currently selected component.

## Visual Overview of IBM Application Navigator 

![overview](https://github.com/IBM/appnav/blob/master/images/appnav-screens.png)

## Built on Open Source, Supported by IBM

IBM Application Navigator is part of 
[IBM Cloud Pak for Applications](https://www.ibm.com/support/knowledgecenter/SSCSJL/welcome.html).  IBM Application Navigator is built from the [kAppNav open source project](https://github.com/kappnav).  The kAppNav technology is included in [Kabanero]((https://kabanero.io/)) application development technology.  IBM Cloud Pak for Applications is built from Kabanero.  

IBM Cloud Pak for Applications, which includes IBM Application Navigator, is a supported project.  The Kabanero and kAppNav open source projects are community supported. 

## References 

1. [kAppNav project page](https://kappnav.io)
1. [Kabanero project page](https://kabanero.io/)
1. [IBM Cloud Pak for Applications](https://www.ibm.com/support/knowledgecenter/SSCSJL/welcome.html)