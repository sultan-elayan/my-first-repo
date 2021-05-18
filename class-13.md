#  Local Storage
> ersistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions

## A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5
> In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.

## INTRODUCING
> What I will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.

## HTML5 STORAGE SUPPORT

- IE 8.0+	
- FIREFOX 3.5+
- SAFARI4.0+
- CHROME4.0+
- OPERA10.5+
- IPHONE2.0+
- ANDROID2.0+

## USING HTML5 STORAGE
> HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

## TRACKING CHANGES TO THE HTML5 STORAGE AREA
> If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.

![](https://camo.githubusercontent.com/453b0b369ef5b8e7d0b78335d2aa429da65e0faedfd52e1cd322b682cbce8b85/68747470733a2f2f7261776769742e636f6d2f6d617231302f706572736973746f2f6d61737465722f6173736574732f6172636869746563747572652e706e673f7261773d74727565)
	
    	
        	
            	
                	
                    	


