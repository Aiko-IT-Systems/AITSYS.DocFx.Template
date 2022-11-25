---
uid: faq
title: Frequently Asked Questions
---

# Frequently Asked Questions

### Code I copied from an article isn't compiling or working as expected. Why?
*Please use the code snippets as a reference; don't blindly copy-paste code!*

The snippets of code in the articles are meant to serve as examples to help you understand how to use a part of the library.<br/>
Although most will compile and work at the time of writing, changes to the library over time can make some snippets obsolete.<br/>
Many issues can be resolved with Intellisense by searching for similarly named methods and verifying method parameters.

### I'm targeting Mono and have exceptions, crashes, or other problems.
As mentioned in the [preamble](xref:preamble), the Mono runtime is inherently unstable and has numerous flaws.<br/>
Because of this we do not support Mono in any way, nor will we support any other projects which use it.

Instead, we recommend using either the latest LTS release or most recent stable version of [.NET Core](https://dotnet.microsoft.com/download).

### Why are you using Newtonsoft.Json when System.Text.Json is available
Yes `System.Text.Json` is available to use but it still doesn't stand up to what we currently need which is why we still use Newtonsoft.Json.
Maybe in time we can switch to your favorite Json Deserializer but for right now we will be using Newtonsoft.Json for the foreseeable future.