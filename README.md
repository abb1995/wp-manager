# wp-manager


Command line interface tool for managing various aspects of wordpress such as theme, plugin, and user management.

## Usage:

wpmanager <command> <action>

Valid Commands:
        theme         - Allows installation, deletion, and activation of themes.
        plugin        - Install, delete, activate, and search for plugins.
        user          - Manage users for current installation.
        status        - Displays information about the current wordpress installation.
        
## Actions
        
Usage - wpmanager theme <action>

Valid actions:
        install       - Install theme using download URL from wordpress.org
        activate      - Activate specified theme.
        delete        - Uninstall specified theme.
        search        - Search wordpress database for provided theme. Enter partial names for bulk searching.
        featured      - List the featured themes from wordpress.org.
        popular       - List popular themes by page.
        list          - Lists currently installed themes.
        
Usage - wpmanager plugin <action>

Valid Actions:
        install       - Install plugin using download URL from wordpress.org.
        activate      - Activate specified plugin.
        deactivate    - Deactivate specified plugin.
        delete        - Uninstall specified plugins.
        search        - Search wordpress database for specified plugin.
        popular       - List popular plugins by page.
        list          - List all currently installed plugins
        
Usage - wpmanager user <action>

Valid actions:
        create         - Create new users.
        changepass     - Change password for users.
        changemail     - Change user's email address.
        changerole     - Change roles for users.
        generate       - Generate multiple random users.
        delete         - Delete users from installation.
        list           - List current users.
