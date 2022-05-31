## Day6 - Review on PrimeReact

####  Author: Zewen Xu, Jiacheng Sun


1. what is it?

   PrimeReact is an UI library. It enbales users a faster access to some pre-designed components like table, graphs in the React environment.

   quick-setup: https://www.primefaces.org/primereact/setup/

2. Pros

   - PrimeReact has various built-in components, ready to go, including:

     | Slider                                        | Tree                                        | Table                                                        |
     | --------------------------------------------- | ------------------------------------------- | ------------------------------------------------------------ |
     | [min, max]: select range                      | draggable: switch on/off node dragging      | sortFunction: customize sorting behavior                     |
     | setp: minimum grid sidth                      | droppable: switch on/off node dropping      | cellEditValidatorEvent: trigger the validation, value includes {"click", "clur", ...} |
     | range: two-boundary selector values           |                                             | editor: enable cell editor input                             |
     | https://www.primefaces.org/primereact/slider/ | https://www.primefaces.org/primereact/tree/ | https://www.primefaces.org/primereact/datatable/             |

   - PrimeReact has built-in plot chart components.

     | Type: {"line", "pie", "radar", "doughnut", "bar"}     |
     | ----------------------------------------------------- |
     | datasets + type: doing combo-chart depicting          |
     | refresh(): redraw the graph                           |
     | https://www.primefaces.org/primereact/chart/doughnut/ |

   - Customized icon library

     https://www.primefaces.org/primereact/slider/

3. Cons

   - Inactive community: PrimeReact(**2.8K star, 500 fork**) has realative low popularity compared to other large open-source UI libraries. It may lack long-term supporting from the development community.

   - IE insupport issue: PrimeReact is not updating their support on IE broswer

     ![image-20220531145807441](/Users/XZW/Library/Application Support/typora-user-images/image-20220531145807441.png)

   - Heavily dependent on CSS: PrimeReact does not provide much styling modification apis(offsets, colors, etc). Users have to face redundant CSS work if they're going to do detialed styling work.

