# Logic of Global Project Tracker ~ "Online community to display projects in progress"

- ## Notes
    - If no viewer perspective specified it counts for every perspective
------------------------------------------------------------------------------------------------------------------------------
- ## Sign up/in 
     - ### Not signed in viewer    
        - Permanent banner on top Signup/Login
------------------------------------------------------------------------------------------------------------------------------
- ## Header home view 
    - ### User
        - **Non edit mode**
            - Username from database (username is requested at sign up can be not empty)
            - Profile picture
            - Button for changing in edit mode
            - About me section
                - If nothing specified than just empty
                - Max 500 words?
            - Clickable links for Home, Browse, Search
        - **Edit mode**
            - If button for edit mode is clicked enter edit mode
            - Change edit button to save button on click
            - Save screen and update database on click
            - Username can be changed like it would be text
            - Changeable profile picture
                - Standard image if no image
                - On click of profile picture galery shows up
                - After clicking on image in gallery view can be choosed
                - Cancel and Apply buttons 
                    - On click Cancel back from full screen profile picture changing view to home view with image not saved
                    - On click Apply back from full screen profile picture changing view to home view with image saved
    - ### Signed in viewer
        - Static header view
        - Back button to last point in History
    - ### Not signed in viewer    
        - Static header view
------------------------------------------------------------------------------------------------------------------------------
- ## Switching between modes home view
    - When click on link load new site
------------------------------------------------------------------------------------------------------------------------------
- ## Project sections home view 
     - ### User
        - Add project button
            - Opens new project mask depending on mode
        - Displays meesage if empty
        - Scrollable feed with loading symbol
        - Displays two projects side by side

    - ### Signed in viewer

    - ### Not signed in viewer    
------------------------------------------------------------------------------------------------------------------------------
- ## Project mask
    - ### User
        - **Non edit mode**
            - Minimized mask in browse view
                - Opens up in new window on click
            - Maximized mask in browse view
                - Backbutton to browse view
                - Visit profile button on click to home view of profile
            - Minimized mask in home view 
                - Toggle bar for making it private or not 
                - Description shows only 100 char and than "..."?
                - Headline 
                    - Mandatory cannot be empty
                - Tags 
                    - maximum of three tags
                - Likes
                - On top image  
                - Error if liking own project
            - Maximized mask in new window
                - Opens up in new window on click
                - Back button to home vie
                - Description without character limit
                - Currently doing
                    - Start date
                    - Progress bar 
                - Want to do 
                - Did
                    - Start date
                    - End date
                - Discontinued 
                    - Start date
                    - End date
                    - Progress bar 
                - Edit button
            - Creation mode
                - Decision private/public
                - Create button on click 
                    - Back on homeview and new project is first position
                    - Error if mandatory fields not filled 
        - **Edit mode**
            - Maximized mask in new window
                - Opens on click edit button 
                - On click edit button save all changes
                - Changeable profile picture
                - Project name, description changeable
                - Start/end date, progress bar changeable if available 
                - Delete button 
                    - Deletes project after confirmation
                    - Loads home view after confirmation    
    - ### Signed in viewer
        - No edit mode available 
    - ### Not signed in viewer   
        - No edit mode available 
------------------------------------------------------------------------------------------------------------------------------
- ## Comments
    - ### User
        - Make a comment section in header
            - Text field for writing comment
                - Min 5 / Max 500 else error 
            - Comment button creates comment on click 
        - Comment itself
            - Upvotes
            - Reply
            - Date 
            - Report
        - Commens with most upvotes on top
        - Each comment in own thread 
        - Message if empty comments
        - Error if like for own comment
    - ### Signed in viewer
    - ### Not signed in viewer   
        - Login to comment button
        - No reply button 
------------------------------------------------------------------------------------------------------------------------------
- ## Explore
    - On standar all is choosen 
    - Header
        - Headline
        - Filter button for filtering for project modes (all is a option)
        - Shows random projects from all users 
    - Scrollable feed with load button
------------------------------------------------------------------------------------------------------------------------------
- ## Search 
    - Searchbar on top 
    - If input in searchbar crawl through tags and headlines and display hits 
    - Scrollable feed 
    - Message for no results 
------------------------------------------------------------------------------------------------------------------------------
- ## Database
    - 
------------------------------------------------------------------------------------------------------------------------------


