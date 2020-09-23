# glitch-migration-for-aframe

This is a quick example for migrating your Glitch.com A-Frame projects to be hosted on Github.

Steps:
1. Make a new GitHub Project

    a. Set it to public.
    
2. In "Settings" on GitHub navigate down to GitHub Pages and active the project as a GitHub page. 

    a. Make the master branch the source.
    
    b. Note the web address.
    
3. Upload the assests used to your new GitHub repo.

    a. Upload them to the root.
    
    b. If errors occur try using the GitHub desktop application to push new files to your repo.
    
        i. Help for adding files can be found here: https://docs.github.com/en/github/managing-files-in-a-repository/adding-a-file-to-a-repository
    
4. Create a new index.html file in your GitHub repo and paste your code in full from Glitch.com.

5. Edit the code the addresses for the assests so they allign with the assests housed on Github.

    a. You are looking for the "<asset-item>" element.
    
    b. The new URL for "src" will = "GitHub Pages web address" + "file name with extension"
    
        i. Example: https://cthompto.github.io/glitch-migration-for-aframe/lock2.gltf
        
6. Navigate to your new page using web address from step 2.

7. Test and share!
