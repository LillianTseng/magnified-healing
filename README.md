# magnified-healing
Automatically exported from code.google.com/p/magnified-healing

**[2021/08/23] Change to 一階線上復習與高深資訊研究課程**
Note: 新網站要用.html,舊網站用 .xml
--

[2020/07/28]Add query-teacher-info.xml for new application to add and view MG teacher profiles
--
-Already added another spreadsheet and form for users to fill in teacher profile, and the fore/sheet is attached with notice and review script.
-This xml is for MG website page https://sites.google.com/site/magnifiedhealingchinese/directory, and the gadget url is http://lilliantseng.github.io/magnified-healing/query-teacher-info.xml, in which the data url is https://docs.google.com/spreadsheets/d/1UfJBgdyejQ21dr4s1fyBtkMYIqZYMUo58b6I6oCIoY0/edit?gid=1844470468&headers=1.
-In show-event.xml, I still use jsapi version 41 for keeping GadgetHelper, but here I update all apis, and since I couldn't find a way to use Prefs to set data url (at google site), I hard coded the data url, hence no need of GadgetHelper.
--------------------------------------------------------------------------------
[2018/02/25] Update entry id for End Date from 1000002 to 1130960036 & change form aciton to real url
--
-Julian made a form for TSL but the form got mixed up with MH form, and one field was missing, so had to add a new field to replace it
-Originally retrieve form action url from MH site widget prefs, but that url https://docs.google.com/spreadsheet/formResponse?formkey=dE4tbHk5MWozVV9LTHFwanEwXzloX3c6MQ doesn't work for some reason, so hard code current form url instead and may put it back to reference in the future if needed.
https://docs.google.com/forms/d/e/1FAIpQLSd6kEDKxEqb0I83R5hnv3x5AQBhrZQX98-zzhJ62I0JCC3VJQ/formResponse
----------------------------------------------------------

[2016/12/9] Add new activity "5擴大療癒法一階One Day Review" in event-postng-form.xml
------------------------------------------------------------------------
[2016/9/23] Upcoming events cannot be shown; originally thought it was because obsolete API, but found out not relative (so rollback to old API). And refresh the share option for SpreadSheet itself and could work.
---

Also update spinning icon to link to in-site gif directly.

Move show event gadget to GitHub (forgot where it was, maybe hosted by google and read only now)
**New xml gadget host url: http://lilliantseng.github.io/magnified-healing/show-event.xml

Gadget attribute:
data source: https://docs.google.com/spreadsheets/d/1v3oovzhqhy2N8OMiHiO7pvLx74MykGPhzF_tjXp4Hqw/gviz/tq?authkey=COG2zIwB&gid=1
(old) https://spreadsheets.google.com/ccc?key=0ApAHxU34jqiRdE4tbHk5MWozVV9LTHFwanEwXzloX3c&hl=en&authkey=COG2zIwB&gid=1
do not refresh
size: 100%, 2000, uncheck all the others

------------------------------------------
[2015/4/20] Google code is shutting down, need to move code to GitHub
--
After moving the codes here, there's no direct access to the xml file, so I use github page to host the xml

**New xml gadget host url: http://lilliantseng.github.io/magnified-healing/event-posting-form.xml

Refer to the followin link, and all the changes will be made in branch gp-pages in the future!!
https://help.github.com/articles/user-organization-and-project-pages/

New gadget src (from src of webpage)
http://biq52h30ismc63qft55p8rpbtqvck23g-a-sites-opensocial.googleusercontent.com/gadgets/ifr?url=http://lilliantseng.github.io/magnified-healing/event-posting-form.xml&amp;container=enterprise&amp;view=default&amp;lang=zh&amp;country=TW&amp;sanitize=0&amp;v=989ea5763e0cf0ce&amp;libs=core:idi:locked-domain&amp;mid=166&amp;parent=https://sites.google.com/site/magnifiedhealingchinese/event-posting-form?pli%3D1#up__event_posting_url&amp;st=e%3DAIHE3cD7qwqUJjfA7p0oHpJvAFWgWUjw4RiAAwmHGaUPf7RvqU3qW8w2PtbCeN%252B0aTy4Ud2j2MaeXNdDfNlIr%252FyKB3FQVtOa3pQFwS8Dx9mmNT%252BsoaV%252BsYpWN7%252FlstYyKMyONgigHCJk%26c%3Denterprise&amp;rpctoken=2438890209113943299

------------------------------------------
[2014/11/3] old widget place can't be access by GGE editor anymore, so I move the form to code.google.com/hosting now
Old widget place: .../event-posting-form.xml
--

http://bhh5bdpscplh84rjnql52mgt41tr73k2-a-sites-opensocial.googleusercontent.com/gadgets/ifr?url=http://hosting.gmodules.com/ig/gadgets/file/100043287795281405772/event-posting-form.xml&container=enterprise&view=default&lang=zh&country=TW&sanitize=0&v=db6a5ac9a0aa9fb1&libs=core:idi:locked-domain&mid=1&parent=http://www.magnifiedhealing-chinese.com/event-posting-form#up__event_posting_url=https://docs.google.com/spreadsheet/formResponse?formkey%3DdE4tbHk5MWozVV9LTHFwanEwXzloX3c6MQ&st=e%3DAIHE3cAT%252FCUc7BnPOzSZsnXXbedb6kk9hI4xafVOOeWJ028g1hfUvXPwPaRSBb6J604h3LlT5SRxOAZimVQV%252FB6aJGY0BjqI6y39wfEUfojKWlPG8i%252BTAM6P%252FpEYFdI72Whk6m3FPTeX%26c%3Denterprise&rpctoken=-8887098246904447956

New widget @
http://magnified-healing.googlecode.com/svn/trunk/event-posting-form.xml

--
event posting url=
https://docs.google.com/spreadsheet/formResponse?formkey=dE4tbHk5MWozVV9LTHFwanEwXzloX3c6MQ
width 100
length 1400
uncheck others
