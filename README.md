Web forgery reporter
====================
There are several aspects of the [existing][existing] web forgery reporter that should be changed:

* [Old][logo] Firefox logo is used.
* Website is neither pretty not Mozilla-style.
* [Phishing link][link-old] should be updated to the one it [redirects to][link-new].
* AFAIK this is the only non-localizable site linked from Firefox.

Here is my proposal for the new design:

* The new Firefox logo is used. :-)
* It is based on [Firefox brand toolkit][brand].
* It resembles [Firefox Input][input] (shall we integrate reporter?).
* Phishing link is updated.
* It should be hosted on Mozilla servers (localizable).

Demo of the proposed Web Forgery Reporter can be found [here][demo].

Report bugs in [Bugzilla bug 691719][bug].

Contributors
------------
* Matjaž Horvat <matjaz@horv.at>

License
-------
    ***** BEGIN LICENSE BLOCK *****
    Version: MPL 1.1/GPL 2.0/LGPL 2.1

    The contents of this file are subject to the Mozilla Public License Version 
    1.1 (the "License"); you may not use this file except in compliance with 
    the License. You may obtain a copy of the License at 
    http://www.mozilla.org/MPL/

    Software distributed under the License is distributed on an "AS IS" basis,
    WITHOUT WARRANTY OF ANY KIND, either express or implied. See the License
    for the specific language governing rights and limitations under the
    License.

    The Original Code is Pontoon.

    The Initial Developer of the Original Code is
    Frederic Wenzel <fwenzel at mozilla dot com>.
    Portions created by the Initial Developer are Copyright (C) 2009
    the Initial Developer. All Rights Reserved.

    Contributor(s):

    Alternatively, the contents of this file may be used under the terms of
    either the GNU General Public License Version 2 or later (the "GPL"), or
    the GNU Lesser General Public License Version 2.1 or later (the "LGPL"),
    in which case the provisions of the GPL or the LGPL are applicable instead
    of those above. If you wish to allow use of your version of this file only
    under the terms of either the GPL or the LGPL, and not to allow others to
    use your version of this file under the terms of the MPL, indicate your
    decision by deleting the provisions above and replace them with the notice
    and other provisions required by the GPL or the LGPL. If you do not delete
    the provisions above, a recipient may use your version of this file under
    the terms of any one of the MPL, the GPL or the LGPL.

    ***** END LICENSE BLOCK *****

[existing]:  http://www.google.com/safebrowsing/report_phish/?tpl=mozilla   "Report Web Forgery"
[logo]: http://www.mozilla.org/en-US/firefox/brand/identity/  "Firefox logo"
[link-old]: http://www.mozilla.org/projects/bonecho/anti-phishing/  "Phishing - old"
[link-new]: http://www.mozilla.org/en-US/firefox/phishing-protection/  "Phishing - new"
[brand]: http://www.mozilla.org/en-US/firefox/brand/  "Firefox Brand Toolkit"
[input]: http://input.mozilla.com/en-US/feedback#happy  "Firefox Input"
[demo]: http://horv.at/forgery/  "Web Forgery Reporter Redesigned"
[bug]: https://bugzilla.mozilla.org/show_bug.cgi?id=691719  "Bug 691719"



