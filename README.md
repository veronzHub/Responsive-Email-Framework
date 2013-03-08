## Overview 
This is a responsive CSS framework for emails. 

* 640px wide with 8 grids


## Usage 
Code the email using tables and apply the desired grid class to the "td" tags the same as you would with the [960 Grid System](http://960.gs/). Do not add dimensions to the HTML, the CSS will handle that.

	<table border="0" align="center" cellpadding="0" cellspacing="0" class="container">
        <tr>
            <td class="grid-2">content content content</td>
            <td class="grid-2">content content content</td>
            <td class="grid-2">content content content</td>
            <td class="grid-2">content content content</td>
        </tr>
	</table>

## Instructions 

After the email is coded, temporarily remove the GLOBAL CSS styling (this section is commented in the CSS). 

    /* START OF GLOBAL RESETS */ 
    body {
        width:100% !important;
        -webkit-text-size-adjust:100%;
        -ms-text-size-adjust:100%;
        margin:0;
        padding:0;
    }
    img {
        outline:none;
        text-decoration:none;
        -ms-interpolation-mode: bicubic;
    }
    table { border-collapse: collapse; }
    table td {
        border-collapse: collapse;
        mso-table-lspace: 0pt;
        mso-table-rspace: 0pt;
        padding: 0;
        font-size: 1px;  /* Outlook 2013 fix for spacers  */
        line-height: 1px; /* Outlook 2013 fix for spacers  */
    }
    a,
    font,
    span { line-height: normal; /* all text needs to be inside span, font, or anchor tags */ }
    .yshortcuts,
    .yshortcuts a,
    .yshortcuts a:link,
    .yshortcuts a:visited,
    .yshortcuts a:hover,
    .yshortcuts a span {
        color: #000;
        text-decoration: none !important;
        border-bottom: none !important;
        background: none !important;
    }
    .ReadMsgBody { width: 100%; }
    .ExternalClass { width: 100%; }
    /* END OF GLOBAL RESETS */

Run the remaining code through this [CSS Inline Tool](http://beaker.mailchimp.com/inline-css). After the CSS is made inline, add the GLOBAL CSS styling back to the head, and remove the INLINE STYLING CSS(this section is commented in the CSS).

## Email Client Support 	

#### Standard Email Clients
* AOL
* Hotmail
* Gmail
* Outlook.com *
* Yahoo!
* Outlook 2003, 2007, 2010, 2013
* Outlook Express
* Entourage 2003, 2008
* Lotus Notes 8, 8.5
* Thunderbird
* Applemail 4
* Windows Mail

####Mobile Email Clients
* Android 2.3, 4
* iPhone 4S (iOS 5), 4S(iOS 6)
* iPad *
* Kindle Fire 2.3

## Tools 

* CSS Inline Tool: [Mail Chimp] (http://beaker.mailchimp.com/inline-css)
* Email testing: [Email on Acid](http://www.emailonacid.com/)
* Calculations: [Instacalc](http://instacalc.com/9710)
* Image placeholders: [Placehold.it](http://placehold.it)


## Resources 

* CSS resets: [HTML Email Boilerplate] (http://htmlemailboilerplate.com/)
* CSS support in email: [Campaign Monitor](http://www.campaignmonitor.com/css/)

## Bugs 

* [iPad](http://www.campaignmonitor.com/blog/post/3585/iphone-fail-the-trouble-with-table-borders-and-html-email)
* Outlook.com in IE9
* Blackberry