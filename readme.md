# Localization Resources of EyeMoveX EMDR application

Contains string resource of our EyeMoveX application for localization.

[![Play Store Badge](https://developer.android.com/images/brand/en_app_rgb_wo_60.png)](https://play.google.com/store/apps/details?id=com.linknext.ace.emdr3)

[EyeMoveX](https://play.google.com/store/apps/details?id=com.linknext.ace.emdr3)

<https://play.google.com/store/apps/details?id=com.linknext.ace.emdr3>

<https://github.com/link-marie/EyeMoveX-resource>

![EyeMoveX](https://lh3.googleusercontent.com/nPFjF_dn0v0TQ7eVKQ_JaOGS2RvvVvHPzvekmbPwkK7heLmlWkX--B7nSgxGuGxni5oH8nILtCzGfYlyevRh2nbXWS771zw7O6DlsXJF2XszGChzhrVkJzKDLM-TDFfdfHtGS1Y=s512-no)


# Get Secret Code by Submitting Your Translation!

By adding translated strings, 
the app will support new language.

If you want to use the app with your mother language,
 please consider to translate the string resources.

When your translation is adopted to this app, 
you will receive *'secret code'* for upgrading the app to paid version!! 

#### Features of Paid Version
- No advertisement
- Sound panning function
- 3D object trajectory
- More control buttons on the main screen

# Languages longing for

We want to support languages such as...

- français - French (fr)
- Deutsch - German (de)
- 한국어 - Korean (ko)
- Nederlands - Dutch (nl)
- Español - Spanish (es)
- Русский - Russian (ru)
- Türkçe - Turkish (tr)
- Português - Portuguese (pt)
- Italiano - Italian (it)
- Norsk - Norwegian (no)
- Svenska - Swedish (sv)
- עברית - Hebrew (he)
- dansk - Danish (da)
- Język Polski - Polish (pl)
- Română - Romanian (ro)
- 中文 - Chinese (zh)
- Arabic (ar)
- català - Catalan (ca)
- ελληνικά - Greek (el)
- eesti - Estonian (et)
- suomi - Finnish (fi)
- hrvatski jezik - Croatian (hr)
- Bahasa Indonesia - Indonesian (id)
- српски језик - Serbian (sr)
- Українська - Ukrainian (uk)
- български език - Bulgarian (bg)
- magyar - Hungarian (hu)
- Slovenčina - Slovak (sk)
- Slovenski Jezik - Slovenian (sl)
- euskara - Basque (eu)
- Persian (fa)
- Íslenska - Icelandic (is)
- Tiếng Việt - Vietnamese (vi)

e.t.c....

# HOW TO CONTRIBUTE
1. Clone or download this resource.
https://github.com/link-marie/EyeMoveX-resource

2. Find and pick *English version* of string files (XML format) and use those as base text

3. Translate English strings to your language. Note that keep the same file structure and format.

4. Submit your translation

   There are two ways of submitting.

   - Pull request to *pull-request* repository if you are familiar with Github. [About pull request](https://help.github.com/articles/about-pull-requests/)
   - Mail us zipped files  (Marie Rijk <rijkmarie@gmail.com>)
    
   Please describe your language code when you submit. 
(reference [Language Code](https://en.wikipedia.org/wiki/ISO_639-1))

5. Receive *'secret code'* for upgrading

   After confirming your work, 
and your translation is adopted to the app, 
you will get a secret code for upgrading the app from *free* to *paid* version!!

![Upgrade Screen](https://github.com/link-marie/EyeMoveX-resource/blob/master/Dept/screen02.png)


# File format

String resources are described in several XML files.
The syntax of contents is as shown below. 

If you need, please refer to [String Resources](https://developer.android.com/guide/topics/resources/string-resource.html)
about the format of the resources in detail.

## Syntax

The contents of string resources are shown below.

```XML
<?xml version="1.0" encoding="utf-8"?>
<resources>

    <string
        name="string_keyword"
        >text_string</string>
        
    <string-array name="string_array">
        <item>text_string</item>
        <item>text_string</item>
        <item>text_string</item>
        <item>text_string</item>
    </string-array>

</resources>
```

Please specify translated text in *'text_string'* part.  


## Formatting Strings

### Line feed

Sometimes you will see the following keyword in string definition.  

    \n

It means newline is inserted in the text at the point.
Just keep the escape sequence as it is.

## Escape keywords
    \&xxx;  such as \&apos;

The keyword start with \\＆ is html escape sequence. 
Just keep the escape sequence as it is.

## Arguments

    %s

or

    %1$s %2$d

Those are argument for string and filled text by programing code.
 Just keep this as it is now.

## Html text

html text can be used surrounded by \<!\[CDATA\[ ---- \]\]\> keyword.  

```XML
<string name="string_html">

<![CDATA[

HTML text in here <br>
with limited set of html 

]]>

</string>


```

Just keep the format as it is.
Please refer to [Formatting and Styling](https://developer.android.com/guide/topics/resources/string-resource.html#FormattingAndStyling) 
 in detail.

# Question?
Please contact to 
Marie Rijk <rijkmarie@gmail.com>


# License

    Copyright LINK-NEXT since 2003

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

