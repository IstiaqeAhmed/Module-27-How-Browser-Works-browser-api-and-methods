# Module-27-How-Browser-Works-browser-api-and-methods
# How to Website Editable? Answer : document.body.contentEditable = true

# 27-2 How Browser works, DOM tree, Render Tree
# When we are write HTMl, CSS, JS Browser work like : Create DOM(Document Object Model) Tree -> parse style -> from this two thing create render tree -> set layout -> paint
# Details: http://onwebdev.blogspot.com/2010/06/firefox-unveiled-gecko-basic-data-flow.html

# 27-3 Website alert, confirmation, prompt to collect data
# repository name: istiaqe-bank and commit: show alert message
# prompt: prompt("Tell me your name") then show This page says then below Tell me your name then Tex box then ok and cancel button 
# Confirm: confirm("Are you coming in the picnic"); then show This page says below Are you coming in the picnic then ok and cancel button 

# 27-4 URL, URL parts, query string, hash, subdomain
# Details: https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL

# 27-5 document location, access href, hash, assign
# website location search type in console: window.location
# website reload: location.reload()
# jump to another website : location.assign("type website url") or location.href = "type url"
# Details: https://developer.mozilla.org/en-US/docs/Web/API/Window/location

# 27-6 history api, back, forward, go, history length
# how many website we load if we want to see type in console : history
# if we want to see previous website type in console : history.back()
# if we want to see next website type in console : history.forward()
#  history.go(3) : website load after 3 website url
# What will you call to see the 3 step back webpage the user was using? ANSWER: go(-3)
# Details: https://developer.mozilla.org/en-US/docs/Web/API/History_API

# 27-7 cookies, dev tool application tab, cookies at server
# cookies indicates which website I visit. 
# cookies can store some data in my browser 
# cookies are send to the server  
# Details: https://developer.mozilla.org/en-US/docs/Web/API/Document/cookie

# 27-8 local storage, session storage, edit storage information
# Details: https://developer.mozilla.org/en-US/docs/Web/API/Storage
# storage name which can store some data in my browser :
# 1. cookies 2. session 3. local
# local storage: https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
# for a long time data store. persistent
# session storage : for a short time data store. when tab open session storage show. tab closed session closed
# Details:https://developer.mozilla.org/en-US/docs/Web/API/Window/sessionStorage

# 27-9 Browser clear cache, chrome extension, web store, restart

# 27-10 Browser Overview, Module Summary
# 1. how to work browser? internal mechanism, v8 engine, rendering engine, layer, 
# alert, confirm, prompt, url, location.href, history api, url part, cookies, storage, event bubble  