First Hack
==========

... If you can call it that much.

Years ago, I was playing the online browser game **Ambar** (since down) in which you had to pick a class which determined what spells you could cast
by selecting it in a simple dropdown. So we were playing an empire in which we grew like mad without training any troops.  
If we could outgrow everyone, no one would be able to open a portal to us, which was kind of the idea because as you can guess
having no troops in a war game usually is.. problematic.

Another empire did manage to open a portal to us however and and that's when I used these local html pages to do some stuff
that was not available to me through the regular web interface.

```html
<base href="http://www.darklights.com/cgi-bin/game/login">
<SELECT CLASS=inputs NAME=magic SIZE=1><option value="0">No Spell Selected</option>
<option value="1">Divine Sight</option>
<option value="2">Echos of the Past</option>
<option value="3">Open Portal</option>
<option value="4">Close Portal</option>
... and more spells here...
</SELECT>
```

I did get an IM from the attacking empire asking how exactly we managed to magically close the portal
since no one in the empire had the required class to do so ;)


Summary
-------

All user input is evil.

Have a backup plan in case plan A goes awry.

I'm a cheat and should be banned.
