# PROJECT NOAH
#### Parametric Modeling made Easy.

---

![Parametric Modeling made Easy.](https://github.com/NyanDesigns/NOAH/blob/main/v.1.0/SourceFiles/IMAGES/BannerEdit.jpg)

---

[![DOWNLOAD HERE](https://github.com/NyanDesigns/NOAH/blob/main/v.1.0/SourceFiles/IMAGES/DownloadHere.png)](https://github.com/NyanDesigns/NOAH/raw/main/v.1.0/noah-setup.exe)

### WHAT IS NOAH?

__PROJECT NOAH__ is an _grasshopper-based_ plugin for _Rhino 3D_ to help Architects, especially students, create a more __Dynamic and Efficient Conceptural Design Workflow__ via automation of Architectural Elements and Processes, _i.e. skip endlessly modeling railings_. __PROJECT NOAH__ is a __free__ and __open source__ project intended to 
- __Help designers efficiently transfer ideas__, from mind or paper sketches, and to _Rhino_ digital space without having to _modeling repetitive elements and performing repetitive commands_ and __dynamically explore more design options__ via modeling parametrically in _grasshopper_.
- __Encourage Begineers__ to __explore__ the _annotated grasshopper script_, __tinker__ with the existing functions, and use _NOAH_ as __reference__ for thier own scripts; learn from my mistakes.
- __Allow Advance Users__ intergate their workflow into _NOAH_ via using the interface system as a backbone framework to __add__ or __modify__ functions to create a more __personalized__ version of _NOAH_.

### WHAT CAN NOAH DO?
#### LIST OF FUNCTIONS
- __CONCEPTURAL__
  - __FORM__ | Creating `massing forms` from `Rhino Curve and Surface` inputs and perform boolean operations.
  - __PATTERN__ | `Place`, `Orient`, `Rotate` and `Scale` an `object geometry` onto a `target geometry`, manipulated by `attractor geometry`. 
- __ARCHITECTURAL__
  - __FLOOR__  |  Create `Slab` from `Rhino Curve and Surface` inputs, with __3__ types of `Tile Patterns` and __3__ types of `Support`.
  - __WALL__  |  Create __5__ differenct types of `Walls` from `Rhino Curve and Surface` inputs.
  - __RAILING__  |  Create __5__ differenct types of `Railings` from `Rhino Curve` inputs.
  - __STAIR__  |  Create `Stairs` from `Rhino Curve` inputs, with different `tread`, `rise` and `stringer` geometry.
  - __PIPE__ (experimental)  |  Create `Pipes` from `Rhino Curve` inputs.
---

### SYSTEM REQUIREMENTS

- OS | __WINDOWS__
- [RHINO](https://www.rhino3d.com/download/) | VERSION __6__ or __7__
- RHINO PLUGINS | 
  - [GRASSHOPPER](https://www.grasshopper3d.com/page/download-1) (included with RRHINO __6__ & __7__)
- GRASSHOPPER PLUGINS | 
  - __1)__ [Human UI.v.0.8.1.3](https://www.food4rhino.com/app/human-ui) 
  - __2)__ [EleFront.v.0.4.1](https://www.food4rhino.com/app/elefront) 
  - __3)__ [Human.v.1.7.2](https://www.food4rhino.com/app/human) 
  - __4)__ [Lunchbox.v.2020.6.30](https://www.food4rhino.com/app/lunchbox) 
  - __5)__ [Pufferfish.v.2.9](https://www.food4rhino.com/app/pufferfish) 
  - __6)__ [MetaHopper.v.1.2.4](https://www.food4rhino.com/app/metahopper) 
  - __7)__ [Weaverbird.v.0.9.0.1](https://www.giuliopiacentino.com/weaverbird/) 
  - __8)__ [TT Toolbox.v.1](https://www.food4rhino.com/app/tt-toolbox)

### RELEASES

- __1.0__ - beta test release

---

### INSTALLATION GUIDE

__1__ | Download from the [latest release](https://github.com/NyanDesigns/NOAH/raw/main/v.1.0/noah-setup.exe).
>  If flagged by `antivirus`, right-click and choose to __KEEP__ file and download to PC.

__2__ | Run [noah-setup.exe](https://github.com/NyanDesigns/NOAH/blob/main/v.1.0/noah-setup.exe) and choose installation for your version of _Rhino_.
> - `full installation` mode includes 1) __NOAH__ 2) __External Plugins__ 3) __Extras__ (extracted to `"_"%Desktop%\NOAH EXTRAS\"_`)
> - `compact installation` mode includes 1) __NOAH__

__3__ | Install all __required plugins__ for _grasshopper_.
> - For `full installation`, navigate to EXTRAS folder `_"%Desktop%\NOAH EXTRAS\"_` and open __INSTALL.gh__. Download All missing plugins from package manager and close.
> - For `compact installation`, download and install all required and missing plugins mannually. Links above.

__4__ | Load NOAH __toolbar__ into Rhino.
> - After starting _Rhino_, navigate to top __"Menu bar> Tools (between Transform and Analyze)> Toolbar Layout.."__ 
> - In Toolbar Options, navigate to top __"File__ (Followed by Edit, Tools)__> Open"__ and open __"N O A H.rui"__ from default path `_"%AppData%\Roaming\McNeel\Rhinoceros\7.0\UI"_`. :ballot_box_with_check:__Checkmark__ "N O A H" to load toolbar and "OK"/ "Save and exit" out of menu.

_4.5_ | BONUS | Load NOAH __alias__ into Rhino for easier access to NOAH. `*Note: Need EXTRAS installed through full installation mode`.
> - Type _rhino command_ __"Options"__ and navigate to __"Alias"__ on the Menu Left Side.
> - Click on __"Import"__ and Navigate to NOAH EXTRAS folder, `_"%Desktop%\NOAH EXTRAS"_`, and select __"ALIAS.txt"__ and "OK"/ "Save and exit" out of menu.
> - Type _NOAH_ in _Rhino_ command bar to start NOAH.

__5__ | Start NOAH by clicking on the button, and have fun exploring!

### TUTORIALS

__COMING SOON!__

---

### CREDITS

__Author__ | NYAN LIN MYAT `@ Nyan | Designs`

### SPECIAL THANKS & ACKNOWLEDGEMENTS
- __David Rutten__ [(Holy Sprit)](https://www.youtube.com/user/DavidMTRutten)
- __Andrew Heumann__ [(The Goat)](https://www.youtube.com/channel/UCxBNmThLKmkzCcJLtgJBqYg)
- [__Junichiro Horikawa__](https://www.youtube.com/channel/UC5NStd0QmACnWs9DzqJ3vHg)
- [__Gediminas Kirdeikis__](https://www.youtube.com/user/Gediminas3)
- [__Alphonso Peluso__](https://www.youtube.com/user/vertexdigitaldesign)
- [__Parametric House__](https://www.youtube.com/c/ParametricHouse/videos)
- [__How to Rhino__](https://www.youtube.com/channel/UCwImuwbI4lKk544-FS7A2Yw)
- [__Paramarch__](https://www.youtube.com/channel/UCk-taU3sDSSyM6qehAJmTRg)
- [__BORSH__](http://borsh.pro/)
- __AND MANY OTHER CREATORS ON YOUTUBE AND RHINOFORUMS.__

---

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/https://github.com/NyanDesigns)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg' alt='instagram' height='40'>](https://www.instagram.com/@nyan_designs/)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/icloud.svg' alt='website' height='40'>](https://projectnoah.webflow.io/)  


