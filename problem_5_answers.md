1. This bar chart is not usable. There is no way to tell what data the bars
are encoding - we need the names of states next to the bars, a title for the
chart, and also some sign of the numerical equivalency of the bar, so that
there is a sense of scale.

2. The first g level translates the origin of the chart to the upper left
corner by setting the left and top margins. The second g level allows for a 
heading or other information to be added above or around the chart. The final
g level contains g elements, each of which corresponds to a single bar, and
each of these g elements contains a rect and a text element.

3. If the rect element is coded before the text element, the bars are drawn
on top of the text for the unemployment rates and therefore they are no longer
visible!
