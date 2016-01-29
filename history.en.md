# History

 - master/HEAD
   * Works on Nightly 47.0a1.
   * Supports e10s.
   * Add "Don't suspend this site automatically" to the tab context menu.
   * Detect host name of web pages more correctly.
   * Visibility options for menu items work correctly.
   * Next focused tab after the current tab is suspended is now configurable.
   * Newly opened background tabs can be suspended by default.
   * Features are available from the context menu on the contents area.
   * Provide ability to limit the number of on-memory tabs.
 - 0.2.2014050201
   * Works on Firefox 29 and Nightly 32.0a1.
   * Drop support for Firefox 25, 26, 27 and 28.
 - 0.1.2013111801
   * Works on Firefox 25 and later.
   * Fixed: Background tabs are suspended correctly after a while, even if there is no exception. (by YosukeM, thanks!)
 - 0.1.2013053101
   * Modified: Just to pass through AMO Editor's review, make codes free from "evalInSandbox()" and E4X. They were still there only for backward compatibilities so they never caused errors/security issues on lately Firefox, however, editors persecutive rejected those codes, then I've given up and removed them.
 - 0.1.2013052901
   * Modified: Some codes depending on "evalInSandbox()" are just removed. AMO Editors always banned new releases, because an included library had codes with "evalInSandbox()" for backward compatibility - even if it is NEVER called on this addon.
   * Modified: Update codes around [session store API](http://dutherenverseauborddelatable.wordpress.com/2013/05/23/add-on-breakage-continued-list-of-add-ons-that-will-probably-be-affected/).
 - 0.1.2013040601
   * Fixed: Restore suspended tab automatically when it is reloaded.
 - 0.1.2012122901
   * Released.
