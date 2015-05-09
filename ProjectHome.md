# Project Update: 30th April 2013 #

Over the last few years I've found very little time to work on LuaInterface. Certain platforms such as Mono/Xamarin and WinRT aren't supported well (if at all) and there are still quite a few bugs open.

I would like to suggest that the community look towards Vinicius Jarina's project on Github called [NLua](https://github.com/NLua/NLua) moving forward.

NLua is a fork of this project and I expect it will see more frequent updates over there than I am able to achieve here on Google Code.

- Craig Presti


---


LuaInterface is a library for integration between the Lua language and Microsoft .NET platform's Common Language Runtime (CLR). Lua scripts can use it to instantiate CLR objects, access properties, call methods, and even handle events with Lua functions.

Information related to this project is also available at http://luaforge.net/projects/luainterface

Note: Since v2, LuaInterface has some dependencies on the VisualC++ runtime library. The recommended way of deploying the dependencies is to install the redist from [here](http://www.microsoft.com/downloads/details.aspx?familyid=9B2DA534-3E03-4391-8A4D-074B9F2BC1BF&displaylang=en).