# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screen reader is a software application that interprets things on the screen (text, images, links, and so on) and converts these to a format that visually impaired people are able to consume and interact with. We should care because it allows everyone to access the site and could prevent your company from getting fined for inaccessible code.
https://www.smashingmagazine.com/2018/12/voiceover-screen-reader-web-apps/#:~:text=A%20screen%20reader%20is%20a,to%20consume%20and%20interact%20with. 

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<img src="https://i.dailymail.co.uk/i/pix/2012/01/12/article-2085622-0F6E403C00000578-802_468x305.jpg"/>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ul>
    <li><a href="https://www.thehamptongallery.com/"></li>
    <li><a href="https://www.inuitartzone.com/?gclid=Cj0KCQjww_f2BRC-ARIsAP3zarFM-jAvxd0G-4rjs_oL3dp0IWt752ksqGImpu5Rjhtg22MXHTMwVUcaAqYhEALw_wcB"></li>
    <li><a href="https://nelson-atkins.org/?gclid=Cj0KCQjww_f2BRC-ARIsAP3zarH-2CufOA9yLFTiqTil2FxgAACzYR20rj_w8zvZujvC6li-yjuZL1YaAn-7EALw_wcB"></li>
</ul>   

c) You want to sell designer hats. You need to receive orders from the user.
<input type="text">
<input type="submit" value="Send Request">

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No, because it is not a block element

## Q5 - What is the most generic tag you can use?

<div></div>

## Q6 - What do the following achronyms stand for?

a) `a` anchor element, creates a hyperlink to web pages

b) `ol` ordered list

c) `ul` unordered list

d) `li` list element

e) `tr` table row element

f) `th` table header

g) `td` table data

## Q7 - Usually, `td` elements are children of what kind of elements?

Block Element

## Q8 - What is the difference between td and th?

table data is info within the table, table headers helps us differentiate the data.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

H1

## Q10 - In which situation can you use self closing tags?

<area />
<base />
<br />
<col />
<embed />
<hr />
<img />
<input />
<link />
<meta />
<param />
<source />
<track />
<wbr />

## Q11 - What is autofilling and why is it important?

The HTML autocomplete attribute allows web developers to control the autocomplete feature to prevent these sorts of scenarios. It works by allowing the websites to control whether sensitive data entered in the form and input elements will be stored in the user’s browser cache.

https://www.netsparker.com/blog/web-security/impact-autocomplete-feature-web-security/#:~:text=The%20HTML%20autocomplete%20attribute%20allows,in%20the%20user's%20browser%20cache.

## Q12 - Which attributes are always present in an img element?

src and alt

## Q13 - Which attribute is always present for an anchor tag?

href
