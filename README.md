# ToolBox.css
A css library that makes tool tips awesome.
## About
 Creating a Tooltip from scratch is a process. The most basic tooltip requires a large amount of code. Here is just an example for one Tooltip

``` 
.tooltip {
  position: relative;
  display: inline-block;
  border-bottom: 1px dotted black; /* If you want dots under the hoverable text */
}


.tooltip .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: black;
  color: #fff;
  text-align: center;
  padding: 5px 0;
  border-radius: 6px;
 
  /* Position the tooltip text - see examples below! */
  position: absolute;
  z-index: 1;
}


.tooltip:hover .tooltiptext {
  visibility: visible;
}


<div class="tooltip">Hover over me
  <span class="tooltiptext">Tooltip text</span>
</div>
```


Nobody wants to do that!! I created a solution to this problem. A Tooltip Library where to invoke the tooltip that you want it's as easy as just adding the class type to the span element. Check out the rest of the Readme to learn how...

## Landing Page


[This way to ToolBox.css](https://bradfabian.github.io/toolBox.css/ "ToolBox.CSS Homepage")

## Demo Of Tooltips
![Demo](
      https://github.com/BradFabian/toolBox.css/blob/master/source/images/TooltipDemo.gif
      )

## How To Use
In your HTML include the CDN LINK:

```<link rel="stylesheet" href="https://s3.amazonaws.com/toolboxcsscdn/toolbox.css">```

Set the div class to tooltip then add a toolbox class to your span

```<div class="tooltip"> Accept <span class="toolbox-accept"> Accepted </span> </div>```


### ToolBox-Classes
| ToolTip Function      | Classes          
| :-------------------: |:-------------:| 
| Bottom Right            | toolbox-bottom-right | 
| Bottom            | toolbox-bottom     | 
| Bottom Left       | toolbox-bottom-left    |
| Left            | toolbox-left | 
| Right           | toolbox-right    | 
| Top Right      | toolbox-top-right  | 
| Top       | toolbox-top | 
| Top Left      | toolbox-top-left  | 
| Accept        | toolbox-accept | 
| Info         | toolbox-info  | 
| Error       | toolbox-error  | 
| Warning           | toolbox-warning| 
| Small Tooltip          | toolbox-small   | 
| Medium Tooltip      | toolbox-med   | 
| Large  Tooltip         | toolbox-large| 
| Always There           | toolbox-always    | 
| Rounded Corners           | toolbox-rounded   | 
| Shadowy      | toolbox-shadow   |
| Fade-in      | toolbox-fade    | 
| Bouncy        | toolbox-bounce | 
| Spinning        | toolbox-spin    | 
| Crazy Color Change      | toolbox-crazy     |        

## Contact Me

If you enjoyed my CSS Library please email me at brad@bradfabian.com . I'm available for any project & can work with the following languages:
HTML CSS JavaScript jQuery React Node Express MongoDB Mysql PHP
Check out my portfolio at www.bradfabian.com 
