# Dependency Confusion Demo

Repository for https://www.meetup.com/dotnetiasi/events/287271942/

Beware of the [Evil_Hacker](https://www.nuget.org/packages/Corporate.Private.Library/1.0.9999)!

Feel free to use this repository to demo in your company or team on how Dependency Confusion works.

And please don't forget to mention me when doing so :).

Thanks.

Checkout the following tags for each demo:
- `demo0` for typosquatting with `Gogle.Protobuf`
- `demo1` for public version of private package `Corporate.Private.Library`
- `demo2` for Package Source Mapping defense for hybrid package source configurations
- `demo3` for `<trustedSigners>` defense for typosquatting and owners updates
- `demo4` for `packages.lock.json` - notice when an unexpected version is used (and the hash of the package)

You can find how to defenct your NuGet supply chain against dependency confusion on my blog: https://andreiepure.ro/2022/08/28/dotnetday-resources.html

TL;DR:
1. Use Package Source Mapping
1. Use `<trusted signers>`
1. Reserve prefixes for both your public and private packages on nuget.org