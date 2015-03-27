# SearchDrivenLabs
a SharePoint website to host sub webs named 'labs' to aggregate the labs content by a search frontend

# ToDo's

- Create a prototype 
    - Create Items in a Taxonomie Store of accessible from the target site
    - Build sitecolumns inherited from std SP and some with values from the new Taxonomie items
    - Build site ContentTypes from our fields
    - Create at least one list and add at liest on from our CT as default to this list(s)
    - Create a new Page
    - Add to this page the Searchresult web part
        - Design the web part and the result template so it looks like the catergy result on ms azureml.net
    - Create a subsite on our website to design on this the ui, associated with our defined meta data, for the search
    - Make a template from this site
        - Maybe delte the subsite
    - Use this template to create a new subsite
    - Check our search setting, so we get the result view in our wished manner
- Save the whole stuff now as a site template (sandboxed wsp)
    - at this moment we have from our core in [PnP](https://github.com/OfficeDev/PnP/blob/master/README.md) no code block to save a site as xml template
    - so we must do it at the moment over the old VS way, we will extrakt from the wsp the xml using our brain
    - after this is done we will craete step bey step from the [Samples](https://github.com/OfficeDev/PnP/tree/master/Samples), Tests and Scenarios our target 
        - on the end we will have one VS project with a complete App the new app way
        - our search page will our primary page
        - we will have a link on this page to our lists, where users are able to do a new request for a new lab or sprint
        - we will have a some logic (workflow) for announcing this request on yammer and an for approval
            - if approved a new subsite will be provisioning
- ..
- Lessions learned
- feel free to make a pull request!
