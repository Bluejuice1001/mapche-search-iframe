1.94
Made changes ot accept multiple domains to bot authenticate when using iframe in crm, to view feasibility tool and test results

1.95
Removed border in StepProduct, signup-modal. Added border: none; to fix

1.96
Added ability to add own colors in crm and change provider colors with a click of a button. Alkso swapped out maps with latest google maps, need to fix the demo key

1.97
Added test otp for isDemo

1.98
Removed devide-y from SearchMenue2 html below to remove border on iframe so that it can blend with any website
<div class="font-sans text-sm w-full max-w-full max-h-full bg-white shadow-catche fixed top-10  flex flex-col divide-y overflow-hidden"

1.99
Changed this.focus() to this.unfocus() SearchBox mounted()
This allow any website to incoroporates the iframe, with out auto focus set. To set focus on click do this manually in html client side

2.00
Added Lat and Lng on search bar, also build in if Lat and Lng not in coutry it displays error message

2.01
Cannot press Search if not both Lat and Lng is filled in 
