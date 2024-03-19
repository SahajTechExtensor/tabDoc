# tabDoc
Doc
+---@fuse
|   |   fuse.module.ts
|   |   index.ts
|   |       
+---app
|   |   app.component.html
|   |   app.component.scss
|   |   app.component.ts
|   |   app.module.ts
|   |   app.resolvers.ts
|   |   app.routing.ts
|   |   http-service.service.ts
|   |   tab-utils-events.ts
|   |   
|   +---core
|   |           
|   +---grid-custom-logic
|   |   |   Accountant-details-grid.ts
|   |   |   all-case-grid.ts
|   |   |   BO-details-grid.ts
|   |   |   closed-case-grid.ts
|   |   |   CM-details-grid.ts
|   |   |   custom-section-grid.ts
|   |   |   enum-details-grid.ts
|   |   |   Expert-details-grid.ts
|   |   |   files-details-grid.ts
|   |   |   FO-details-grid.ts
|   |   |   mbv-case-grid.ts
|   |   |   mbv-prepare-questions-grid.ts
|   |   |   mbv-questions-detail-grid.ts
|   |   |   open-case-grid.ts
|   |   |   out-of-tat-case-grid.ts
|   |   |   pending-for-allocation-case-grid.ts
|   |   |   pending-in-closure-case-grid.ts
|   |   |   pending-in-field-case-grid.ts
|   |   |   pending-in-qc-case-grid.ts
|   |   |   pending-in-release-case-grid.ts
|   |   |   pending-in-tat-case-grid.ts
|   |   |   pmjay-case-grid.ts
|   |   |   pmjay-prepare-questions-grid.ts
|   |   |   pmjay-questions-detail-grid.ts
|   |   |   prepare-questions-grid.ts
|   |   |   questions-detail-grid.ts
|   |   |   reinvestigate-case-grid.ts
|   |   |   sla-schemes-grid.ts
|   |   |   
|   |   \---PMS
|   |           Time-Log-Grid.ts
|   +---layout
|   |   |   layout.component.html
|   |   |   layout.component.scss
|   |   |   layout.component.ts
|   |   |   layout.module.ts
|   |   |   layout.types.ts
|   |   |   
|   |   +---common
|   |   |   +---languages
|   |   |   |       
|   |   |   +---messages
|   |   |   |       
|   |   |   +---notifications
|   |   |   |       
|   |   |   +---screen-filter
|   |   |   |       
|   |   |   +---search
|   |   |   |       
|   |   |   +---settings
|   |   |   |       
|   |   |   +---shortcuts
|   |   |   |       
|   |   |   \---user
|   |   |           
|   |   \---layouts
|   |       +---empty
|   |       |       
|   |       +---horizontal
|   |       |   +---centered
|   |       |   |       
|   |       |   +---enterprise
|   |       |   |       
|   |       |   +---material
|   |       |   |       
|   |       |   \---modern
|   |       |           
|   |       \---vertical
|   |           +---classic
|   |           |       
|   |           +---classy
|   |           |       
|   |           +---compact
|   |           |       
|   |           +---dense
|   |           |       
|   |           +---futuristic
|   |           |       
|   |           \---thin
|   |                   
|   +---loader           
|   |               
|   +---modules
|   |   +---admin
|   |   |   +---Home
|   |   |   |       Home.component.css
|   |   |   |       Home.component.html
|   |   |   |       Home.component.ts
|   |   |   |       Home.module.ts
|   |   |   |       
|   |   |   +---star
|   |   |   |       star-json.ts
|   |   |   |       star-standard-json.ts
|   |   |   |       star.component.html
|   |   |   |       star.component.scss
|   |   |   |       star.component.spec.ts
|   |   |   |       star.component.ts
|   |   |   |       star.formio.ts
|   |   |   |       star.module.ts
|   |   |   |       
|   |   |   +---tab-basic-grid
|   |   |   |       tab-basic-grid-json.ts
|   |   |   |       tab-basic-grid-standard-json.ts
|   |   |   |       tab-basic-grid.component.css
|   |   |   |       tab-basic-grid.component.html
|   |   |   |       tab-basic-grid.component.spec.ts
|   |   |   |       tab-basic-grid.component.ts
|   |   |   |       tab-basic-grid.formio.ts
|   |   |   |       ui-tab-basic-grid.module.ts
|   |   |   |       
|   |   |   +---new-tab-query-builder
|   |   |   | 
|   |   |   +---tab-blueprint
|   |   |   |           
|   |   |   +---tab-chart-component
|   |   |   |       
|   |   |   +---tab-child-screen-renderer
|   |   |   |       
|   |   |   +---tab-color-picker
|   |   |   |       
|   |   |   +---tab-comments
|   |   |   |       
|   |   |   +---tab-custom-calender
|   |   |   |       
|   |   |   +---tab-custom-chips
|   |   |   |       
|   |   |   +---tab-custom-code-editor
|   |   |   |       
|   |   |   +---tab-custom-form-builder
|   |   |   |       
|   |   |   +---tab-custom-gantt-chart
|   |   |   |       
|   |   |   +---tab-custom-imageupload
|   |   |   |       
|   |   |   +---tab-custom-pivot-table
|   |   |   |       
|   |   |   +---tab-custom-place-picker-map
|   |   |   |           
|   |   |   +---tab-custom-richtext-html-editor
|   |   |   |       
|   |   |   +---tab-custom-track-map
|   |   |   |       
|   |   |   +---tab-date-range-picker
|   |   |   |       
|   |   |   +---tab-dropdown-tree
|   |   |   |       
|   |   |   +---tab-file-preview
|   |   |   |       
|   |   |   +---tab-form-builder
|   |   |   |       
|   |   |   +---tab-form-renderer
|   |   |   |       
|   |   |   +---tab-history
|   |   |   |           
|   |   |   +---tab-iframe
|   |   |   |       
|   |   |   +---tab-pdf-viewer
|   |   |   |       
|   |   |   +---tab-query-builder
|   |   |   |       
|   |   |   +---tab-skeleton
|   |   |   |       
|   |   |   +---tab-textbox
|   |   |   |       
|   |   |   +---tab-timer
|   |   |   |       
|   |   |   +---tab-tree-view
|   |   |   |       
|   |   |   +---tab-widget
|   |   |   |       
|   |   |   \---transition-preview
|   |   |               
|   |   +---auth
|   |   |   +---confirmation-required
|   |   |   |       
|   |   |   +---forgot-password
|   |   |   |       
|   |   |   +---reset-password
|   |   |   |       
|   |   |   +---sign-in
|   |   |   |       
|   |   |   +---sign-out
|   |   |   |       
|   |   |   +---sign-up
|   |   |   |       
|   |   |   \---unlock-session
|   |   |           
|   |   \---landing
|   |       \---home
|   |               home.component.html
|   |               home.component.ts
|   |               home.module.ts
|   |               home.routing.ts
|   |               
|   +---screen-custom-logic
|   |   |   blueprint-screen.ts
|   |   |   Custom-Activity-Screen.ts
|   |   |   Detail-Custom-View-Screen.ts
|   |   |   Detail-layout-screen.ts
|   |   |   DSQ-Details-screen.ts
|   |   |   DSQ-Sorting-screen.ts
|   |   |   Entity-edit-screen.ts
|   |   |   grid-setting-screen.ts
|   |   |   lookup-configuration-screen.ts
|   |   |   permission-control-screen.ts
|   |   |   plugin-render.ts
|   |   |   Release-Detail-Screen.ts
|   |   |   Release-List-Screen.ts
|   |   |   screen-designer.ts
|   |   |   Share-Record-screen.ts
|   |   |   sla-schemes-screen.ts
|   |   |   
|   |   +---Phoenix
|   |   |       
|   |   \---PMS
|   |           
|   \---shared
|       |   shared.module.ts
|       |   
|       +---pipes
|       |       
|       +---services
|		|
|       |       
|       \---templates
|           |   
|           +---tab-dynamic-dialog
|           |       
|           +---tab-dynamic-sidebar
|           |       
|           \---tab-timer-component
| 

