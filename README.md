# READ ME
This repository is created to save style packages for PDF output and webhelp output. These styles are created through Oxygen Style Basket: https://styles.oxygenxml.com.  Packages are saved in https://github.com/iesdocs/styles/tree/main/publishing_templates.

## Current workitems

https://github.com/iesdocs/styles/blob/main/workitems.md 

## How to Customize Style with Oxygen 
1. Go to https://styles.oxygenxml.com. 
2. Configure each attribute.
3. Click **See Results** to preview the effect in PDF or Webhelp.
4. Download the style package: **Download** > **Publishing Template**.

## How to Apply the Style to Oxygen 
In Oxygen XML Editor, you need to select a transformation scenario before publishing a book in a certain format. The most frequently used format in IES DOCS is PDF. So the following instruction takes customizing PDF transformation as an example.

**Procedure**:
1. Open oXygen XML Editor v23.1.
2. Select **DITA Maps** > **Configure Transformation Scenarios**. ![image](https://user-images.githubusercontent.com/49274541/126759829-74eb1fbe-4a00-4f5b-9619-a230025de927.png)
3. Select **DITA Map PDF - based on HTML5 & CSS**. ![image](https://user-images.githubusercontent.com/49274541/126759535-afa97ada-e77a-4945-8879-c6965389f3c7.png)
4. Click **Edit**.
5. Click **Yes** to duplicate and edit the scenario. ![image](https://user-images.githubusercontent.com/49274541/126760029-6755cba7-83d8-4983-aa52-2a75f9c8b7c7.png)
6. Specify the name of this custom transformation scenario in the **Edit Scenario** window. ![image](https://user-images.githubusercontent.com/49274541/126760265-efe8ccec-ada7-4091-a41d-4efc2826b62a.png)
7. Click **Choose Custom Publishing Template**.![image](https://user-images.githubusercontent.com/49274541/126760420-2f2fc6c6-94c8-4d2d-8da4-aee5781eb20f.png)
8. Browse for a publishing template from local folder. 
9. Click **OK**.![image](https://user-images.githubusercontent.com/49274541/126760747-36142c30-b581-42ca-beed-1613a61f20f8.png)
10. Click **OK** to save the settings.

## How to Generate PDF Using a Custom Transformation Scenario
![image](https://user-images.githubusercontent.com/49274541/126761226-9f522bc0-dfba-41cc-9ce3-6caca82c06ff.png)

## Size

A4 Landscape: 3508 X 2480

## Margin
 
0.295in

## Color

### Forest Green
rgb(4,65,35)
HEX=044123.

### Green
rgb(3,181,133)
HEX=03B585.

### Black
rgb(13,13,13)
HEX=0D0D0D.

### BlackgroundAccentColor/TableStripe Color
rgb(230,255,250)
HEX=E6FFFA

## Tools

### Style Design Tools
https://styles.oxygenxml.com 

### Authoring Tools
- If you are authoring in DITA, try oXygen XML editor. The latest version is 23.1. https://www.oxygenxml.com/doc/versions/23.1/ug-editor/index.html 
- If you are working in Markdown, you have various options, for example, notepad, visual studio code, atom, notepad++, github desktop, gitkraken, oxygen, or web editor embedded in Github, that is, here.
- If you are working on image processing, Adobe Illustrator.
- Currently, I'm testing the https://www.oxygenxml.com/oxygen-xml-web-author/app/oxygen.html. The oXygen XML Web Author.

### Source File Management Tool
- In the current test, I use Gitkraken. See https://nio365.sharepoint.com/:p:/r/sites/IESDocumentation/Shared%20Documents/Dita%20Migration/_Git%20it%20done.pptx?d=w394f1262f2e245bbae27ca9f7a6361f0&csf=1&web=1&e=qC2mEy 
- Github Desktop is also convenient to use as a tool but it lacks support to AzDo. 
- oXygen 23.1 supports Git Staging too.

### Background Generator
- https://bggenerator.com 
- http://bg.siteorigin.com 
- https://www.adobe.com/express/create/background

### RGB2HEX Color Convertor
- https://www.rgbtohex.net
- https://www.rapidtables.com/convert/color/rgb-to-hex.html 

## Installation and Configuration
See https://nio365.sharepoint.com/:p:/r/sites/IESDocumentation/Shared%20Documents/Dita%20Migration/_Git%20it%20done.pptx?d=w394f1262f2e245bbae27ca9f7a6361f0&csf=1&web=1&e=qC2mEy 

Note that since most of the tests were done in Gitlab, so the majority part of the content in the ppt above are mainly for Gitlab users. But the steps in Gitkraken is roughtly the same, just replace Gitlab with Github. Of course, the ppt will be updated soon.

## Output Generation
- If you are working with lwDITA + Markdown, or, MDITA, open a ditamap or a topic and generate the output from oXygen XML Editor.
- If you are working with pure Markdown, the Preview mode in almost every editor allows you to check the actual effect. Be careful with the Markdown syntax. See: https://www.markdownguide.org/getting-started/ and https://learnxinyminutes.com/docs/markdown/.

## Tables in Markdwon
Table creation and maintenance could be annoying even after months of experience with MD. There are some handy tools you can use to speed up the table creation or modification, aka. Table Generator. See https://jakebathman.github.io/Markdown-Table-Generator/ and https://www.tablesgenerator.com/markdown_tables.

## Contact
galano.han@ni.com or galano.han@outlook.com



