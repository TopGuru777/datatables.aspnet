<h1>Datatables.AspNet</h1>
<<<<<<< HEAD
Formely known as <strong>DataTables.Mvc</strong>, this project startedwith small objectives around 2014, aiming to provide intermediate and experienced developers a tool to avoid the boring process of handling DataTables parameters.<br />
More than a year later and after a full rewrite we are now proud to support Asp.net MVC, WebApi and Asp.Net Core (full .NET Core support).<br />
Unit-testing is a priority to avoid breaking <i>your</i> app and every stable release should provide better and wider test cases.

<h3>Stable 2.0.0 version is here!</h3>
`2.0.0` stable release now ships with full support for DotNet Core 1.0.0, along with extensions, tests and all the fun we can get.
This is the first stable version for `DataTables.AspNet`. We dropped the full migration path because we made everything clean and simple and included some basic usage samples to guide you.

<h3>Standard NuGet packages</h3>
- [DataTables.AspNet.Mvc5](https://www.nuget.org/packages/DataTables.AspNet.Mvc5/) with support for Mvc5, registration and automatic binders
- [DataTables.AspNet.WebApi2](https://www.nuget.org/packages/DataTables.AspNet.WebApi2/) with support for WebApi2, registration and automatic binders
- [DataTables.AspNet.AspNetCore](https://www.nuget.org/packages/DataTables.AspNet.AspNetCore/) with support for AspNetCore, dependency injection and automatic binders

<h3>IMPORTANT: Deprecated (unlisted) package</h3>
- [DataTables.AspNet.AspNet5](https://www.nuget.org/packages/DataTables.AspNet.AspNet5/)

This package has been replaced by DataTables.AspNet.AspNetCore due to Microsoft renaming of the new platform.

<h3>Write your own code!</h3>
DataTables.AspNet ships with a core project called [DataTables.AspNet.Core](https://www.nuget.org/packages/DataTables.AspNet.Core/), which contains basic interfaces and core elements just the way DataTables needs.<br />
Feel free to use it and implement your own classes, methods and extend DataTables.AspNet in <i>your</i> very own way.

<h3>Helpers and extensions</h3>
- [DataTables.AspNet.Extensions.AnsiSql](https://www.nuget.org/packages/DataTables.AspNet.Extensions.AnsiSql/) enables basic translation from sort and filter into ANSI-SQL `WHERE` and `ORDER BY`
- [DataTables.AspNet.Extensions.DapperExtensions](https://www.nuget.org/packages/DataTables.AspNet.Extensions.DapperExtensions/) transforms filters into `IPredicate` and sort into `ISort`

Those are still alpha1 releases but with nuget packages available. There are no tests yet, they are in a very initial phase and might change a bit in the near future.
After they become stable I'll accept pull requests for other extensions (eg: NHibernate, EntityFramework, etc). For now, keep in mind that these two are supposed to set the basic extension standard for DataTables.AspNet.Extensions.

<h3>Samples</h3>
Samples are provided on the `samples` folder.<br />
There is no wiki yet. I will start writing a very gorgeous wiki, just don't know when. Tons of work and no time. Sorry.
I am open to contributors :)

<h3>Eager for some new code?</h3>
If you are, check out [dev](https://github.com/ALMMa/datatables.aspnet/tree/dev) branch. It has the latest code for DataTables.AspNet, including samples and more.<br />
For every release (even unstable ones) there should be a nuget package.

<h3>Stable code?</h3>
For production code, I do recommend the `master` branch. It holds the stable version. Every stable version has a stable Nuget release.<br />

<h3>Still legacy?</h3>
Drop it!<br />
2.0.0 (stable) is faster, better coded and fully tested. DataTables.Mvc is now completely discontinued.

<h3>Known issues</h3>
- There are some issues while trying to run all tests simultaneously. I'll try to fix that by including some test ordering.
- Extension methods do not have tests yet and should not be used on production code.
=======
Formely known as <strong>DataTables.Mvc</strong>, this project started over a year ago with small objectives, aiming to provide intermediate and experienced developers a tool to avoid the boring process of handling DataTables parameters.<br />
More than 15 months later, we now undergo a full rewrite with support for Mvc, WebApi and AspNet (<strong>core CLR included!</strong>).<br />
Also, unit-testing is a priority to avoid breaking <i>your</i> app.

<h3>Beta2 has just arrived!</h3>
`Beta2` release now ships with updated support for Asp.Net 5 RC1 Update1, along with all the goodies from `Beta1`.
This is the second beta release for `DataTables.AspNet`. A full migration path (for all, including MVC 5 and WebApi) will be released as soon as Asp.Net 5 becomes stable enough to stop changing namespaces (before that, it would require multiple migration paths and paths from previous paths and so on).

<h3>NuGet packages</h3>
- [DataTables.AspNet.Mvc5](https://www.nuget.org/packages/DataTables.AspNet.Mvc5/), with support for Mvc5, registration and automatic binders
- [DataTables.AspNet.WebApi2](https://www.nuget.org/packages/DataTables.AspNet.WebApi2/) with support for WebApi2, registration and automatic binders
- [DataTables.AspNet.AspNet5](https://www.nuget.org/packages/DataTables.AspNet.AspNet5/) with support for AspNet5, dependency injection and automatic binders

You can extend DataTables.AspNet easier through [DataTables.AspNet.Core](https://www.nuget.org/packages/DataTables.AspNet.Core/), which contains core elements including standard interfaces and enums.

<h3>Samples</h3>
Samples are provided on the `samples` folder.<br />
You can also check our wiki (TODO - Wiki) for guidance.

<h3>Migration path</h3>
Check a full migration path from older versions of `DataTables.AspNet` up to the most recent one.<br />
`Beta1` also delivered some breaking changes so if you're running alpha code, check the second migration path bellow:

- Migration path from legacy DataTables.Mvc (TODO - Wiki)
- Migration path from alpha releases (TODO - Wiki)

<h3>Eager for some new code?</h3>
If you are, check out [dev](https://github.com/ALMMa/datatables.aspnet/tree/dev) branch. It has the latest code for DataTables.AspNet, including samples and more.<br />

<h3>Stable code?</h3>
We're still on beta so there is no stable code/release on `master` branch yet.<br />
As soon as we're stable, `master` branch will be populated, tagging will get in place and and Nuget packages will drop the `-Pre` argument.

<h3>Still legacy?</h3>
If you can, drop it!<br />
Beta1 is just as stable as legacy DataTables.Mvc and if you find any bug you can easily submit and get it fixed ASAP.

<h3>Known issues with Beta2</h3>
I has been a nightmare to make tests run properly. Since beta2 I simply can't make them run correctly so I'll rely on updated sample projects to make sure everything works fine and will rewrite tests and try to make them run again.
>>>>>>> refs/remotes/origin/master
