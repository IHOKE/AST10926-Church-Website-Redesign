<h1>AST10926 Church Website Redesign</h1>

<h2>Description</h2>
<p>This repo is a complete <b>redesign and rebuild</b> of the <a href="https://github.com/IHOKE/AST10962-GPJ">previous repo</a> from scratch.</p>

<h2>Features</h2>
<p>After learning from the previous project, this project is rebuilt from the ground up,<br>
with much more focus on readability and ease of maintainance.<br>
This includes better formatting, indents, CSS variables,<br>
separating CSS files into common(used by index and all subpages) and specific CSS for each page.<br>
Making it much more easier to change anything (less likely to go insane).</p>

<h2>Patch Notes</h2>

<hr>
<h3>v0.2 - Finishing Index</h3>
<hr>
<p>Index is &#40;probably&#41; finished, will probably move onto subpages, or other stuffs.</p>
<p>- Finished Section "About".</p>
<p>- Sick scrollbar section using webkit in "About"</p>
<p>- Added Section "Committee".</p>
<p>- Added Section "Credits" for well, credits.</p>
<p>- Section "Committee responds to resizing to about 600px width size."</p>
<p>- [Bug] Found and patched a (CSS) bug in Footer where it may induce spacing when "Credits" is used on top of it.</p>
<p>- The first and last "News" buttons will no longer show top and bottom borders respectively.</p>
<p>- [Bug] "Banner" GSAP animation may induce width when viewport width is about 400px or smth.</p>
<p>- [Bug] Styles of section "About" and "affl_grid_follow_grid_title" is consistent on Firefox. (lazy to fix)</p>

<hr>
<h3>v0.1 - Initial Commit</h3>
<hr>
<h4><i>From the last project</i></h4>
<p>- Redesigned Nav bar & Footer.</p>
<p>- Changed palette.</p>
<p>- Added Section "News", contains a sidebar with a list of buttons and preview panel on the other side to show news content.</p>
<p>- Added Section "About Us", Only the container is built, no actual content is available atm.</p>
<p>- [common.css] Stores Nav bar / Footer / Palettes and other variables to be used by all pages including index.
<p>- [index.css] CSS file to be used only by index.html, other css files will be named in a similar manner.
<p>- Added drop shadows to various places</p>
