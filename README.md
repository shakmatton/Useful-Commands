<h3>Cloning a specific branch from a repository</h3>

    git clone -b <branch_name> <git_chosen_cloning_method_url> 

    or

    git clone --single-branch --branch <branch_name> <cloning_url>

<h3>Degit</h3>

    npm install -g degit       [Installation]

    degit user/repo            [Master branch]
    degit user/repo#dev        [Specific Branch ("dev")]

    degit user/repo my-new-project    [New folder]

    degit user/repo/subdirectory      [Clone specific directory]
    
    degit user/repo my-new-project my_destination_folder_path    [Specific usage]

<h3>Github problem</h3>

    Error: You Have Not Concluded Your Merge (MERGE_HEAD Exists)
    
    **Solution:** git commit -m "commit message"
