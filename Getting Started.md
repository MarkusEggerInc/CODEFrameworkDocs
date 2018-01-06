# Getting Started

## Installing the Framework Tools

The easiest way to get started with the CODE Framework, is to install the CODE Framework Tools Visual Studio Extension through the Visual Studio Extension Manager:

![](Getting%20Started/Figure1.png)

Once these extensions are installed, new project templates become available in Visual Studio, such as these:

![](Getting%20Started/Figure2.png)

Note that this does not install the actual framework, but only the tools. However, if you use a template that requires framework components (such as the CODE Framework WPF MVVM/MVC template), the tools detect the dependency and show a dialog like this:

![](Getting%20Started/Figure3.png)

Using this dialog, CODE Framework assemblies can be added to the current project, either by adding files stored locally in a folder or ZIP file (after having downloaded the desired version manually from CodePlex), or you can let the tool retrieve the latest version from CodePlex for you and add the assemblies directly.

Note that CODE Framework assemblies are generally not installed in the GAC (although you could do so yourself if you prefer this option) but they are put into a dummy location in the local solution. This has the advantage that different solutions built with the CODE Framework can use different versions without colliding with each other, and allowing the developer full control over when and to what version a certain solution is to be upgraded to. It also has the advantage that all external assemblies can be checked into source control, allowing other developers to simply join the project through source control without relying on additional installs. This also allows them to always retrieve the correct version of these dependencies automatically. This generally works very well for typical business applications.

For more information and samples, please see the article links at the top of this page.

## Next Steps

CODE Framework covers a wide range of features. This includes handling of services (from server-side service creation and hosting, to client-side service calling) as well as a rich framework for client-side development.

To understand services, see [Understanding Services](Understanding-Services). To learn more about the WPF UI framework, see topics such as [Understanding Layout](Understanding-Layout).

