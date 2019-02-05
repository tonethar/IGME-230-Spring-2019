# Week 3B - Responsive Design and Media Queries
## (RIT was closed, class cancelled... This material will be covered in the first class of the 4th week).

## Topics
- Responsive Design
- CSS Media Queries
- Intro to Flexbox and CSS Grid layout

Responsive design all boils down to a visual design that responds to the size of a user's device or screen. Flexible, "liquid" layouts are one part of this, but to optimize the experience for any given device we often need to utilize custom CSS for each device. Enter: media queries!

This involves two parts. First, in your CSS:

```
@media screen and (max-width: 480px) {
  */ note that you can target multiple screen widths, using multiple media queries /*
  */ Style rules here that adapt to the smaller screen /*	
} 
```

and then in the head of your HTML:

``` 	
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
```

Combining media queries with other advanced CSS layout techniques can make responsive design much easier to implement.  With mobile traffic exceeding traditional desktop traffic on major websites, it is important to make sure that your pages work on a variety of screen (as well as print), and not just high-resolution computer and laptop displays.  

The "Responsive Design with CSS Media Queries" exercise below uses responsive design techniques coupled with some basic CSS layout methods such as floats to achieve the desired effect.  In some-ways, this design was created first with desktop in mind and utilizes techniques to make it acceptable for mobile users as well.  This is sometimes thought of as "graceful degradation"... experiencing the best version of the site on desktop, but still having be at least usable on mobile.

Another way of thinking about designing websites is to think first about what you want the essential experience of your website to be and then design it for "Mobile-first" and give the site "progressive enhancements" as the larger display capabilities become available.

The Flexbox and CSS Grid layout methods that we'll briefly demo today are powerful tools to make responsive web-layouts that keep your HTML markup clean and semantic without a lot of extra added elements to make the layout "work".


## Reference
- http://getbootstrap.com/
- http://www.templatemo.com/

We will look at Bootstrap and other frameworks later, but for now it's nice to see how it does responsive design!

## Media Query Resources
- http://www.w3.org/TR/css3-mediaqueries/
- http://webdesignerwall.com/tutorials/responsive-design-with-css3-media-queries
- http://cssmediaqueries.com/

## Flexbox Resources
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://flexboxfroggy.com/  or for an alternate challenge:  http://www.flexboxdefense.com/
- https://flexboxpatterns.com/

## CSS Grid Resources
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
- https://css-tricks.com/snippets/css/complete-guide-grid/
- https://cssgridgarden.com/
- https://gridbyexample.com/

## Presentations
- [Responsive Design](https://github.com/tonethar/IGME-230-Master/tree/master/presentations/4B-Responsive-Design.pdf)

## Demo
- [Responsive page demo](https://github.com/tonethar/IGME-230-Master/tree/master/other-files/Responsive_Demo.zip)
- Download flex-grid-demo-files.zip from myCourses for Flexbox and CSS Grid demo.

## Exercise
- [Optional Flexbox Notes/Exercise](https://github.com/dccircuit/IGME-230-Spring-2019/blob/master/weekly/flexbox-ex.md)
- [Responsive Design with CSS Media Queries](https://github.com/tonethar/IGME-230-Master/tree/master/exercises/week-4/ICE-ResponsiveCSS.pdf)
- [Responsive Design start files](https://github.com/tonethar/IGME-230-Master/tree/master/exercises/week-4/darth_start_files.zip)

<hr><hr>

| <-- Previous Unit | Home | Next Unit -->
| --- | --- | --- 
| [**week-03A-notes.md**](week-03A-notes.md)     |  [**IGME-230 Schedule**](../schedule.md) | [**week-04A-notes.md**](week-04A-notes.md)

