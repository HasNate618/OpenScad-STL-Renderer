\# OpenSCAD STL Renderer



A simple Bash script to automatically generate 8 rendered views (4 top, 4 bottom) of any `.stl` model using \[OpenSCAD](https://openscad.org/).



---



\## Requirements



\- \*\*Install OpenSCAD\*\* 

```

winget install --id=OpenSCAD.OpenSCAD -e

```



---



\## Usage



```

render\_stl.sh model.stl \[--parallel]

```



\- Replace `model.stl` with your stl

\- The argument `--parallel` can be included to render images in parallel but is more resource intensive

\- Renders 8 views of stl into `renders` subdirectory

