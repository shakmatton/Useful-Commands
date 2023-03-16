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

<h3>Github problems & solutions</h3>

    "Error: You Have Not Concluded Your Merge (MERGE_HEAD Exists)"
    
    SOLUTION: git commit -m "commit message"
    
<h3>How to disable Svelte a11y warnings in VScode:</h3>

    a) View > Command Palette > Settings -> Open User Settings (JSON).

    b) Inside ".vscode/settings.json", add this to the end of the file:

    {
        "svelte.plugin.svelte.compilerWarnings": {
          "a11y-aria-attributes": "ignore",
          "a11y-incorrect-aria-attribute-type": "ignore",
          "a11y-unknown-aria-attribute": "ignore",
          "a11y-hidden": "ignore",
          "a11y-misplaced-role": "ignore",
          "a11y-unknown-role": "ignore",
          "a11y-no-abstract-role": "ignore",
          "a11y-no-redundant-roles": "ignore",
          "a11y-role-has-required-aria-props": "ignore",
          "a11y-accesskey": "ignore",
          "a11y-autofocus": "ignore",
          "a11y-misplaced-scope": "ignore",
          "a11y-positive-tabindex": "ignore",
          "a11y-invalid-attribute": "ignore",
          "a11y-missing-attribute": "ignore",
          "a11y-img-redundant-alt": "ignore",
          "a11y-label-has-associated-control": "ignore",
          "a11y-media-has-caption": "ignore",
          "a11y-distracting-elements": "ignore",
          "a11y-structure": "ignore",
          "a11y-mouse-events-have-key-events": "ignore",
          "a11y-missing-content": "ignore",
          "unused-export-let": "ignore",
          "a11y-click-events-have-key-events": "ignore",
          "a11y-no-noninteractive-tabindex":"ignore",
        },
        "nuxt.isNuxtApp": false
      }
