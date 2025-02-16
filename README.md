# Dust Light ▪ Theme for Notepad++

![Dust Light theme for Notepad++, example 1](https://i.ibb.co/98dxyLJ/Dust-Light-example-1.png)
![Dust Light theme for Notepad++, example 2](https://i.ibb.co/MZdB70Z/Dust-Light-example-2.png)
![Dust Light theme for Notepad++, example 3](https://i.ibb.co/j6k2H9s/Dust-Light-example-3.png)

# Description

A theme built around a very subtle shade of gray I call dust gray. It's completely unused/undiscovered color. It has a morsel of magenta in it that you wouldn't normally notice. All other colors of the theme serve to keep this fragile shade in tune, while they're also aligned to each other.

### Supported languages

Assembly, Bash, Batch, C, C++, C#, CSS, HTML, INI, Java, JavaScript, JSON, Lua, Markdown\*, PHP, Python, Ruby, SQL, XML, YAML  
Everything else is usable but not arranged.  
If the theme gets somewhat popular, I'll optimize more languages. (Especially on request of course.)

> \* For Markdown, read the *Setting up Markdown* section at the bottom of this page.

# Installation

1. **Click** [`HERE`](https://github.com/benelaci/NPP-Dust-Light-Theme/archive/refs/heads/main.zip) to download all files in zip.
2. Go to **%APPDATA%\Notepad++**.
3. Open **themes** folder, or create a new folder named **themes** if it doesn't exists.
4. Install the xml in any of the following ways:
   - Copy the **.xml** file in the downloaded zip into the folder. Or
   - Import it to Notepad++ by going to *Menu -> Settings -> Import -> Import Style theme(s)*.
5. Restart Notepad++.
6. Open *Settings -> Style Configurator*.
7. Select theme **Dust Light** from the theme drop-down box.
8. Click **Save & Close**.

# Font

After much fiddling, I found that the basic **Consolas** font was the best fit.  
I recommend turning DirectWrite on because that way the font is somewhat thicker.

![direct write on](https://i.ibb.co/hgvbD7n/direct-Write.png)

# Setting up Markdown

In the downloaded zip there is a Markdown directory. Copy `markdown.DustLight.udl.xml` to `%AppData%\Notepad++\userDefineLangs`

By default, if you open a Markdown file in NPP, the colors may be messed up, because another Markdown UDL is arbitrarily used instead of `Markdown (Dust Light)`, and you have to select the correct UDL in the *Language* menu every time you open a .md file. As this practice is intolerable, it's worth putting a little work into avoiding it:

Open **all** Markdown UDLs in the `userDefineLangs` directory for editing, **except** `markdown.DustLight.udl.xml`. There you can see the following code:

```
<NotepadPlus>
    <UserLang name="Markdown (Theme Name)" ext="md markdown" udlVersion="2.1">
```

Replace `ext="md markdown"` to `ext=""` in all opened documents.

This way the Dust Light UDL will be the only relevant one to be associated with Markdown.

# Author / contact

Laci Bene · laci.bene![|](https://i.ibb.co/7WLcqb3/ch1.gif)mail![|](https://i.ibb.co/R45zkLX/ch2.gif)ee
