CheatSheet 

Git
cd = change directory
mkdir = make directory
To save:
git add .
git commit -m "message"
git push origin master

CSS
class uses .
id uses #

Responsive CSS
html { /* MOBILE */
  font-size: 15px;
}
@media (min-width: 400px) {
  html { /* TABLET */
    font-size: 18px;
  }
}
@media (min-width: 768px) {
  html { /* DESKTOP */
    font-size: 21px;
  }
}

(Evans Notes)
.my-wrapper .my-class{
    /* will apply only to "my-class" elements that are WITHIN "my-wrapper" */
}
.class-one, .class-two{
    /* applies to both classes */
}
.class-one > .child {
    /* only direct children */
}
.class-one.class-two {
    /* must have BOTH of these classes */
}

px
%: percentage of the elements parent
vw/vh: percentage viewheight or viewwidth
rem: ratio of the root font-size

.class{
    color: blue; /* for text color */
    background: red; /* background color */
    width: 5rem;
    max-width: 100vw;
    height: 10%;
    max-height: 100vh;
    margin: 20px; /* outside the element */
    padding: 20px; /* inside */
    font-size: 10px;
    font-family: 'Avenir', Helvetica;
}

HTML
<div>: standard box with nothing pre-defined

<span>: for a little text

<img>: image... it can have a "src" and "alt"

<header>, <footer>, <main>

<a href="google.com"> I am a link </a>: link. It has an "href" prop

<button>

<input />: a text input