# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

## Reporting a Vulnerability

Use this section to tell people how to report a vulnerability.

Tell them where to go, how often they can expect to get an update on a
reported vulnerability, what to expect if the vulnerability is accepted or
declined, etc.
zsh: command not found: -m
netmanagement@iMac-de-steve braintree_node-master % pip install cli
Defaulting to user installation because normal site-packages is not writeable
ERROR: Could not find a version that satisfies the requirement cli (from versions: none)
ERROR: No matching distribution found for cli
WARNING: You are using pip version 21.2.4; however, version 24.0 is available.
You should consider upgrading via the '/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip' command.
netmanagement@iMac-de-steve braintree_node-master % pip install stripe cli
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: stripe in /Users/netmanagement/Library/Python/3.9/lib/python/site-packages (9.10.0)
ERROR: Could not find a version that satisfies the requirement cli (from versions: none)
ERROR: No matching distribution found for cli
WARNING: You are using pip version 21.2.4; however, version 24.0 is available.
You should consider upgrading via the '/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip' command.
netmanagement@iMac-de-steve braintree_node-master % pip install zettle
Defaulting to user installation because normal site-packages is not writeable
Collecting zettle
  Downloading zettle-0.0.1-py3-none-any.whl (1.6 kB)
Installing collected packages: zettle
Successfully installed zettle-0.0.1
WARNING: You are using pip version 21.2.4; however, version 24.0 is available.
You should consider upgrading via the '/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip' command.
netmanagement@iMac-de-steve braintree_node-master % -m pip install --upgrade pip
__vsc_escape_value:print:23: bad option: - 
zsh: command not found: -m
netmanagement@iMac-de-steve braintree_node-master % pip install --upgrade pip
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: pip in /Library/Developer/CommandLineTools/Library/Frameworks/Python3.framework/Versions/3.9/lib/python3.9/site-packages (21.2.4)
Collecting pip
  Using cached pip-24.0-py3-none-any.whl (2.1 MB)
Installing collected packages: pip
  WARNING: The scripts pip, pip3, pip3.10 and pip3.9 are installed in '/Users/netmanagement/Library/Python/3.9/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed pip-24.0
WARNING: You are using pip version 21.2.4; however, version 24.0 is available.
You should consider upgrading via the '/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip' command.
netmanagement@iMac-de-steve braintree_node-master % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"                                                                                               
==> Checking for `sudo` access (which may request your password)...
Password:
Sorry, try again.
Password:
==> This script will install:
/opt/homebrew/bin/brew
/opt/homebrew/share/doc/homebrew
/opt/homebrew/share/man/man1/brew.1
/opt/homebrew/share/zsh/site-functions/_brew
/opt/homebrew/etc/bash_completion.d/brew
/opt/homebrew

Press RETURN/ENTER to continue or any other key to abort:
==> /usr/bin/sudo /usr/sbin/chown -R netmanagement:admin /opt/homebrew
==> Downloading and installing Homebrew...
Reset branch 'stable'
==> Updating Homebrew...
Updated 1 tap (homebrew/cask).
Warning: /opt/homebrew/bin is not in your PATH.
  Instructions on how to configure your shell for Homebrew
  can be found in the 'Next steps' section below.
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run these two commands in your terminal to add Homebrew to your PATH:
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/netmanagement/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh

netmanagement@iMac-de-steve braintree_node-master % brew install stripe/stripe-cli/stripe
zsh: command not found: brew
netmanagement@iMac-de-steve braintree_node-master % stripe_1.20.0_mac-os_x86_64.tar.gz
zsh: command not found: stripe_1.20.0_mac-os_x86_64.tar.gz
netmanagement@iMac-de-steve braintree_node-master % stripe login --interactive
zsh: command not found: stripe
netmanagement@iMac-de-steve braintree_node-master %  var util = require("util");
    var qs = require("./querystring");
zsh: missing delimiter for 'u' glob qualifier
zsh: unknown file attribute: q
netmanagement@iMac-de-steve braintree_node-master % var str = qs.parse("foo=bar&baz=qux");
    util.log(JSON.stringify(str)); // => {"foo":"bar","baz":"qux"}
zsh: invalid mode specification
zsh: no matches found: util.log(JSON.stringify(str))
netmanagement@iMac-de-steve braintree_node-master % str = qs.parse("foo[bar][][bla]=baz");
    util.log(JSON.stringify(str)); // => {"foo":{"bar":[{"bla":"baz"}]}}

zsh: invalid mode specification
zsh: no matches found: util.log(JSON.stringify(str))
netmanagement@iMac-de-steve braintree_node-master % var util = require("util");
    var qs = require("./querystring");

    var obj = {"foo":"bar","baz":"qux"};
    util.log(qs.stringify(obj)); // => foo=bar&baz=qux

    obj = {"foo":{"bar":[{"bla":"baz"}]}};
    util.log(qs.stringify(obj)); // => foo%5Bbar%5D%5B%5D%5Bbla%5D=baz
zsh: missing delimiter for 'u' glob qualifier
zsh: unknown file attribute: q
zsh: command not found: var
zsh: no matches found: util.log(qs.stringify(obj))
netmanagement@iMac-de-steve braintree_node-master % docker run -it -v="$(PWD):/braintree-node" --net="host" braintree-node /bin/bash
zsh: command not found: docker
netmanagement@iMac-de-steve braintree_node-master % docker run -i -v="$(PWD):/braintree-node" --net="host" braintree-node /bin/bash -l -c "npm install;npm run lint"
zsh: command not found: docker
netmanagement@iMac-de-steve braintree_node-master % 
 *  Historique restauré 

netmanagement@iMac-de-steve braintree_node-master %zsh: command not found: from
zsh: unknown file attribute: _
zsh: command not found: class
zsh: missing end of string
zsh: missing end of string
zsh: command not found: assert
zsh: command not found: self._in_main_context
zsh: command not found: try:
zsh: command not found: with
zsh: command not found: yield
zsh: command not found: finally:
zsh: command not found: self._in_main_context
zsh: missing end of string
zsh: command not found: assert
zsh: number expected
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % >....                                                                                                                                                     
        msg = [f'unknown command "{cmd_name}"']
        if guess:
            msg.append(f'maybe you meant "{guess}"')

        raise CommandError(" - ".join(msg))

    # all the args without the subcommand
    cmd_args = args[:]
    cmd_args.remove(cmd_name)

    return cmd_name, cmd_args

zsh: parse error near `()'
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % >....                                                                                                                                                     

    # Needed for locale.getpreferredencoding(False) to work
    # in pip._internal.utils.encoding.auto_decode
    try:
        locale.setlocale(locale.LC_ALL, "")
    except locale.Error as e:
        # setlocale can apparently crash if locale are uninitialized
        logger.debug("Ignoring error %s when setting locale", e)
    command = create_command(cmd_name, isolated=("--isolated" in cmd_args))

    return command.main(cmd_args)

quote> >....                                                                                                                                                                                                                  
        for option in self._get_all_options():
            assert option.dest is not None
            default = defaults.get(option.dest)
            if isinstance(default, str):
                opt_str = option.get_opt_string()
                defaults[option.dest] = option.check_value(opt_str, default)
        return optparse.Values(defaults)

    def error(self, msg: str) -> None:
        self.print_usage(sys.stderr)
        self.exit(UNKNOWN_ERROR, f"{msg}\n")

function dquote> >....                                                                                                                                                                                                        
def get_download_progress_renderer(
    *, bar_type: str, size: Optional[int] = None
) -> DownloadProgressRenderer:
    """Get an object that can be used to render the download progress.

    Returns a callable, that takes an iterable to "wrap".
    """
    if bar_type == "on":
        return functools.partial(_rich_progress_bar, bar_type=bar_type, size=size)
    else:
        return iter  # no-op, when passed an iterator

dquote> >....                                                                                                                                                                                                                 
            format_control=options.format_control,
            allow_all_prereleases=options.pre,
            prefer_binary=options.prefer_binary,
            ignore_requires_python=ignore_requires_python,
        )

        return PackageFinder.create(
            link_collector=link_collector,
            selection_prefs=selection_prefs,
            target_python=target_python,
        )

zsh: parse error near `)'
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % >....                                                                                                                                                     
    # We don't want to clutter the output with control characters if we're
    # writing to a file, or if the user is running with --quiet.
    # See https://github.com/pypa/pip/issues/3418
    elif not file.isatty() or logger.getEffectiveLevel() > logging.INFO:
        yield
    else:
        file.write(HIDE_CURSOR)
        try:
            yield
        finally:
            file.write(SHOW_CURSOR)

zsh: parse error near `)'
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % SUCCESS = 0
ERROR = 1
UNKNOWN_ERROR = 2
VIRTUALENV_NOT_FOUND = 3
PREVIOUS_BUILD_DIR_ERROR = 4
NO_MATCHES_FOUND = 23

zsh: command not found: SUCCESS
zsh: command not found: ERROR
zsh: command not found: UNKNOWN_ERROR
zsh: command not found: VIRTUALENV_NOT_FOUND
zsh: command not found: PREVIOUS_BUILD_DIR_ERROR
zsh: command not found: NO_MATCHES_FOUND
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % 
 *  Historique restauré 

(.venv) netmanagement@iMac-de-steve braintree_node-master % pip install braintree
pip install stripe
Traceback (most recent call last):
  File "/Users/netmanagement/Downloads/braintree_node-master/.venv/bin/pip", line 5, in <module>
    from pip._internal.cli.main import main
  File "/Users/netmanagement/Downloads/braintree_node-master/.venv/lib/python3.9/site-packages/pip/_internal/cli/main.py", line 10, in <module>
    from pip._internal.cli.autocompletion import autocomplete
ImportError: cannot import name 'autocomplete' from 'pip._internal.cli.autocompletion' (/Users/netmanagement/Downloads/braintree_node-master/.venv/lib/python3.9/site-packages/pip/_internal/cli/autocompletion.py)
Traceback (most recent call last):
  File "/Users/netmanagement/Downloads/braintree_node-master/.venv/bin/pip", line 5, in <module>
    from pip._internal.cli.main import main
  File "/Users/netmanagement/Downloads/braintree_node-master/.venv/lib/python3.9/site-packages/pip/_internal/cli/main.py", line 10, in <module>
    from pip._internal.cli.autocompletion import autocomplete
ImportError: cannot import name 'autocomplete' from 'pip._internal.cli.autocompletion' (/Users/netmanagement/Downloads/braintree_node-master/.venv/lib/python3.9/site-packages/pip/_internal/cli/autocompletion.py)
(.venv) netmanagement@iMac-de-steve braintree_node-master % import braintree
import stripe

# Initialize Braintree client
braintree.Configuration.configure(
    braintree.Environment.Sandbox,
    merchant_id='YOUR_MERCHANT_ID',
    public_key='YOUR_PUBLIC_KEY',
    private_key='YOUR_PRIVATE_KEY'
)

# Initialize Stripe client
stripe.api_key = 'YOUR_STRIPE_API_KEY'
zsh: command not found: import
zsh: command not found: import
zsh: command not found: #
zsh: unknown file attribute: \n
(.venv) netmanagement@iMac-de-steve braintree_node-master % git config --global user.name "Nagle Steve"      
(.venv) netmanagement@iMac-de-steve braintree_node-master % git config --global user.email "nagle@webtechnicom
.net"
(.venv) netmanagement@iMac-de-steve braintree_node-master % 
(.venv) netmanagement@iMac-de-steve braintree_node-master % PAYPAL_CLIENT_ID=AUXzJYOJLmX7RD0HtfSgGcq16pSXG6e2kdGj9awLHxTWOmO-dOGMdkUiiTXgDd5ghrVk0tTbHn-LkWFT 
  PAYPAL_CLIENT_SECRET=EBrQ0xy_ougQKZRUZb6sdPJUTUCEklyoGK_Rr0lSmPnhbzP3MCNHp976hrz1TzY-G6bWSUANg9BYlBsNzsh: command not found: -m
netmanagement@iMac-de-steve braintree_node-master % pip install cli
Defaulting to user installation because normal site-packages is not writeable
ERROR: Could not find a version that satisfies the requirement cli (from versions: none)
ERROR: No matching distribution found for cli
WARNING: You are using pip version 21.2.4; however, version 24.0 is available.
You should consider upgrading via the '/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip' command.
netmanagement@iMac-de-steve braintree_node-master % pip install stripe cli
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: stripe in /Users/netmanagement/Library/Python/3.9/lib/python/site-packages (9.10.0)
ERROR: Could not find a version that satisfies the requirement cli (from versions: none)
ERROR: No matching distribution found for cli
WARNING: You are using pip version 21.2.4; however, version 24.0 is available.
You should consider upgrading via the '/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip' command.
netmanagement@iMac-de-steve braintree_node-master % pip install zettle
Defaulting to user installation because normal site-packages is not writeable
Collecting zettle
  Downloading zettle-0.0.1-py3-none-any.whl (1.6 kB)
Installing collected packages: zettle
Successfully installed zettle-0.0.1
WARNING: You are using pip version 21.2.4; however, version 24.0 is available.
You should consider upgrading via the '/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip' command.
netmanagement@iMac-de-steve braintree_node-master % -m pip install --upgrade pip
__vsc_escape_value:print:23: bad option: - 
zsh: command not found: -m
netmanagement@iMac-de-steve braintree_node-master % pip install --upgrade pip
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: pip in /Library/Developer/CommandLineTools/Library/Frameworks/Python3.framework/Versions/3.9/lib/python3.9/site-packages (21.2.4)
Collecting pip
  Using cached pip-24.0-py3-none-any.whl (2.1 MB)
Installing collected packages: pip
  WARNING: The scripts pip, pip3, pip3.10 and pip3.9 are installed in '/Users/netmanagement/Library/Python/3.9/bin' which is not on PATH.
  Consider adding this directory to PATH or, if you prefer to suppress this warning, use --no-warn-script-location.
Successfully installed pip-24.0
WARNING: You are using pip version 21.2.4; however, version 24.0 is available.
You should consider upgrading via the '/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip' command.
netmanagement@iMac-de-steve braintree_node-master % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"                                                                                               
==> Checking for `sudo` access (which may request your password)...
Password:
Sorry, try again.
Password:
==> This script will install:
/opt/homebrew/bin/brew
/opt/homebrew/share/doc/homebrew
/opt/homebrew/share/man/man1/brew.1
/opt/homebrew/share/zsh/site-functions/_brew
/opt/homebrew/etc/bash_completion.d/brew
/opt/homebrew

Press RETURN/ENTER to continue or any other key to abort:
==> /usr/bin/sudo /usr/sbin/chown -R netmanagement:admin /opt/homebrew
==> Downloading and installing Homebrew...
Reset branch 'stable'
==> Updating Homebrew...
Updated 1 tap (homebrew/cask).
Warning: /opt/homebrew/bin is not in your PATH.
  Instructions on how to configure your shell for Homebrew
  can be found in the 'Next steps' section below.
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run these two commands in your terminal to add Homebrew to your PATH:
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/netmanagement/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh

netmanagement@iMac-de-steve braintree_node-master % brew install stripe/stripe-cli/stripe
zsh: command not found: brew
netmanagement@iMac-de-steve braintree_node-master % stripe_1.20.0_mac-os_x86_64.tar.gz
zsh: command not found: stripe_1.20.0_mac-os_x86_64.tar.gz
netmanagement@iMac-de-steve braintree_node-master % stripe login --interactive
zsh: command not found: stripe
netmanagement@iMac-de-steve braintree_node-master %  var util = require("util");
    var qs = require("./querystring");
zsh: missing delimiter for 'u' glob qualifier
zsh: unknown file attribute: q
netmanagement@iMac-de-steve braintree_node-master % var str = qs.parse("foo=bar&baz=qux");
    util.log(JSON.stringify(str)); // => {"foo":"bar","baz":"qux"}
zsh: invalid mode specification
zsh: no matches found: util.log(JSON.stringify(str))
netmanagement@iMac-de-steve braintree_node-master % str = qs.parse("foo[bar][][bla]=baz");
    util.log(JSON.stringify(str)); // => {"foo":{"bar":[{"bla":"baz"}]}}

zsh: invalid mode specification
zsh: no matches found: util.log(JSON.stringify(str))
netmanagement@iMac-de-steve braintree_node-master % var util = require("util");
    var qs = require("./querystring");

    var obj = {"foo":"bar","baz":"qux"};
    util.log(qs.stringify(obj)); // => foo=bar&baz=qux

    obj = {"foo":{"bar":[{"bla":"baz"}]}};
    util.log(qs.stringify(obj)); // => foo%5Bbar%5D%5B%5D%5Bbla%5D=baz
zsh: missing delimiter for 'u' glob qualifier
zsh: unknown file attribute: q
zsh: command not found: var
zsh: no matches found: util.log(qs.stringify(obj))
netmanagement@iMac-de-steve braintree_node-master % docker run -it -v="$(PWD):/braintree-node" --net="host" braintree-node /bin/bash
zsh: command not found: docker
netmanagement@iMac-de-steve braintree_node-master % docker run -i -v="$(PWD):/braintree-node" --net="host" braintree-node /bin/bash -l -c "npm install;npm run lint"
zsh: command not found: docker
netmanagement@iMac-de-steve braintree_node-master % 
 *  Historique restauré 

netmanagement@iMac-de-steve braintree_node-master %zsh: command not found: from
zsh: unknown file attribute: _
zsh: command not found: class
zsh: missing end of string
zsh: missing end of string
zsh: command not found: assert
zsh: command not found: self._in_main_context
zsh: command not found: try:
zsh: command not found: with
zsh: command not found: yield
zsh: command not found: finally:
zsh: command not found: self._in_main_context
zsh: missing end of string
zsh: command not found: assert
zsh: number expected
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % >....                                                                                                                                                     
        msg = [f'unknown command "{cmd_name}"']
        if guess:
            msg.append(f'maybe you meant "{guess}"')

        raise CommandError(" - ".join(msg))

    # all the args without the subcommand
    cmd_args = args[:]
    cmd_args.remove(cmd_name)

    return cmd_name, cmd_args

zsh: parse error near `()'
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % >....                                                                                                                                                     

    # Needed for locale.getpreferredencoding(False) to work
    # in pip._internal.utils.encoding.auto_decode
    try:
        locale.setlocale(locale.LC_ALL, "")
    except locale.Error as e:
        # setlocale can apparently crash if locale are uninitialized
        logger.debug("Ignoring error %s when setting locale", e)
    command = create_command(cmd_name, isolated=("--isolated" in cmd_args))

    return command.main(cmd_args)

quote> >....                                                                                                                                                                                                                  
        for option in self._get_all_options():
            assert option.dest is not None
            default = defaults.get(option.dest)
            if isinstance(default, str):
                opt_str = option.get_opt_string()
                defaults[option.dest] = option.check_value(opt_str, default)
        return optparse.Values(defaults)

    def error(self, msg: str) -> None:
        self.print_usage(sys.stderr)
        self.exit(UNKNOWN_ERROR, f"{msg}\n")

function dquote> >....                                                                                                                                                                                                        
def get_download_progress_renderer(
    *, bar_type: str, size: Optional[int] = None
) -> DownloadProgressRenderer:
    """Get an object that can be used to render the download progress.

    Returns a callable, that takes an iterable to "wrap".
    """
    if bar_type == "on":
        return functools.partial(_rich_progress_bar, bar_type=bar_type, size=size)
    else:
        return iter  # no-op, when passed an iterator

dquote> >....                                                                                                                                                                                                                 
            format_control=options.format_control,
            allow_all_prereleases=options.pre,
            prefer_binary=options.prefer_binary,
            ignore_requires_python=ignore_requires_python,
        )

        return PackageFinder.create(
            link_collector=link_collector,
            selection_prefs=selection_prefs,
            target_python=target_python,
        )

zsh: parse error near `)'
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % >....                                                                                                                                                     
    # We don't want to clutter the output with control characters if we're
    # writing to a file, or if the user is running with --quiet.
    # See https://github.com/pypa/pip/issues/3418
    elif not file.isatty() or logger.getEffectiveLevel() > logging.INFO:
        yield
    else:
        file.write(HIDE_CURSOR)
        try:
            yield
        finally:
            file.write(SHOW_CURSOR)

zsh: parse error near `)'
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % SUCCESS = 0
ERROR = 1
UNKNOWN_ERROR = 2
VIRTUALENV_NOT_FOUND = 3
PREVIOUS_BUILD_DIR_ERROR = 4
NO_MATCHES_FOUND = 23

zsh: command not found: SUCCESS
zsh: command not found: ERROR
zsh: command not found: UNKNOWN_ERROR
zsh: command not found: VIRTUALENV_NOT_FOUND
zsh: command not found: PREVIOUS_BUILD_DIR_ERROR
zsh: command not found: NO_MATCHES_FOUND
(.venv) (.venv) netmanagement@iMac-de-steve braintree_node-master % 
 *  Historique restauré 

(.venv) netmanagement@iMac-de-steve braintree_node-master % pip install braintree
pip install stripe
Traceback (most recent call last):
  File "/Users/netmanagement/Downloads/braintree_node-master/.venv/bin/pip", line 5, in <module>
    from pip._internal.cli.main import main
  File "/Users/netmanagement/Downloads/braintree_node-master/.venv/lib/python3.9/site-packages/pip/_internal/cli/main.py", line 10, in <module>
    from pip._internal.cli.autocompletion import autocomplete
ImportError: cannot import name 'autocomplete' from 'pip._internal.cli.autocompletion' (/Users/netmanagement/Downloads/braintree_node-master/.venv/lib/python3.9/site-packages/pip/_internal/cli/autocompletion.py)
Traceback (most recent call last):
  File "/Users/netmanagement/Downloads/braintree_node-master/.venv/bin/pip", line 5, in <module>
    from pip._internal.cli.main import main
  File "/Users/netmanagement/Downloads/braintree_node-master/.venv/lib/python3.9/site-packages/pip/_internal/cli/main.py", line 10, in <module>
    from pip._internal.cli.autocompletion import autocomplete
ImportError: cannot import name 'autocomplete' from 'pip._internal.cli.autocompletion' (/Users/netmanagement/Downloads/braintree_node-master/.venv/lib/python3.9/site-packages/pip/_internal/cli/autocompletion.py)
(.venv) netmanagement@iMac-de-steve braintree_node-master % import braintree
import stripe

# Initialize Braintree client
braintree.Configuration.configure(
    braintree.Environment.Sandbox,
    merchant_id='YOUR_MERCHANT_ID',
    public_key='YOUR_PUBLIC_KEY',
    private_key='YOUR_PRIVATE_KEY'
)

# Initialize Stripe client
stripe.api_key = 'YOUR_STRIPE_API_KEY'
zsh: command not found: import
zsh: command not found: import
zsh: command not found: #
zsh: unknown file attribute: \n
(.venv) netmanagement@iMac-de-steve braintree_node-master % git config --global user.name "Nagle Steve"      
(.venv) netmanagement@iMac-de-steve braintree_node-master % git config --global user.email "nagle@webtechnicom
.net"
(.venv) netmanagement@iMac-de-steve braintree_node-master % 
(.venv) netmanagement@iMac-de-steve braintree_node-master % PAYPAL_CLIENT_ID=AUXzJYOJLmX7RD0HtfSgGcq16pSXG6e2kdGj9awLHxTWOmO-dOGMdkUiiTXgDd5ghrVk0tTbHn-LkWFT 
  PAYPAL_CLIENT_SECRET=EBrQ0xy_ougQKZRUZb6sdPJUTUCEklyoGK_Rr0lSmPnhbzP3MCNHp976hrz1TzY-G6bWSUANg9BYlBsN  
