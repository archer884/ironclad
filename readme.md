
# Ironclad

Ironclad is a command line tool for creating and managing encrypted password databases.

    $ ironclad --help

      Ironclad is a command line password manager.

    Flags:
      -h, --help        Print the application's help text and exit.
      -v, --version     Print the application's version number and exit.

    Basic Commands:
      add               Add a new entry to a password database.
      delete            Delete one or more entries from a database.
      edit              Edit an existing database entry.
      gen               Generate a new random password.
      init              Initialize a new password database.
      list              List database entries.
      new               Add a new entry to a database. (Alias for 'add'.)
      pass              Copy a password to the clipboard.
      show              List database entries showing full details.
      user              Copy a username to the clipboard.

    Additional Commands:
      config            Set or print a configuration option.
      decrypt           Decrypt a file.
      dump              Dump a database's internal JSON data store.
      encrypt           Encrypt a file.
      export            Export entries from a database.
      import            Import entries into a database.
      purge             Purge deleted entries from a database.
      tags              List database tags.

    Command Help:
      help <command>    Print the specified command's help text and exit.

See the application's [homepage][] for details and download links for pre-compiled binaries.

[homepage]: http://mulholland.xyz/dev/ironclad/
