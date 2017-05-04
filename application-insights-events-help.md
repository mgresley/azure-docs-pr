# Events Help

The Events tool can help you understand how often certain pages and features of your app are used. Then by splitting the data further, it can uncover insights like why certain pages and features received more usage than others.

## Querying for Certain Sessions
Explore different groups of events and page views by adjusting the query options at the top of the Events tool:
**Who used:** Choose custom events and page views.
**During:** Choose a time range.
**By:** Choose how to bucket the data, either by an amount of time or by another property like browser or city.
**Split By:** Choose a dimension by which to split or segment the data.
**Add Filters:** Limit the query to certain events and page views based on their properties like browser or city.

## How Events and Page Views are Counted
A page view represents one occurrence of a user loading a page on your site. Page views are generated automatically by the Application Insights JavaScript SDK when a user loads a page. Additional page views can be added manually in code using the SDK.

A custom event represents one occurrence of something happening in your app, often a user interaction like a button click or the completion of some task. Custom events are generated manually in code using the Application Insights SDK.

## Saving and Sharing Reports
You can save Events reports, either private just to you in the My Reports section, or shared with everyone else with access to this Application Insights resource in the Shared Reports section. 

While saving a report or editing its properties, choose "Current Relative Time Range" to save a report will continuously refreshed data, going back some fixed amount of time. 

Choose "Current Absolute Time Range" to save a report with a fixed set of data. Keep in mind that data in Application Insights is only stored for 90 days, so if more than 90 days have passed since a report with an absolute time range was saved, the report will appear empty.

## Example Events
TBD - explain more when the feature is done. 

## Insights
The Insights sidebar shows large clusters of events and page views that share common properties. These clusters can uncover surprising trends in how people use your app, like if for example 40% of all of the usage of your app comes from people in a single country using a single feature. 
