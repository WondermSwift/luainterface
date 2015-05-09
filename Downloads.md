## Requirements ##
Since v2, LuaInterface has some dependencies on the VisualC++ runtime library. The recommended way of deploying the dependencies is to install the redist from [here](http://www.microsoft.com/downloads/details.aspx?familyid=9B2DA534-3E03-4391-8A4D-074B9F2BC1BF&displaylang=en).

## Changelog ##

What's new in LuaInterface 2.0.3

---

  * Fix: Private methods accessible via LuaInterface
  * Fix: Method overload lookup failures
  * Fix: Lua DoFile memory leaks when file not found (submitted by Paul Moore)
  * Fix: Lua Dispose not freeing memory (submitted by Paul Moore)
  * Fix: Better support for accessing indexers
  * Fix: Parsing error for MBCS characters (qingrui.li)
  * Fix: Dispose errors originating from LuaTable, LuaFunction, LuaUserData
  * Fix: LuaInterface no longer disposes the state when passed one via the overloaded constructor
  * Added: LoadString and LoadFile (submitted by Paul Moore)
  * Added: Overloaded DoString
  * Added: Lua debugging support (rostermeier)

See full [changelog](changelog.md).

Download: http://luainterface.googlecode.com/files/LuaInterface_2.0.3.7z