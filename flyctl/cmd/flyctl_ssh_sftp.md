Get or put files from a remote VM.

## Usage
~~~
flyctl ssh sftp [command] [flags]
~~~

## Available Commands
* [find](/docs/flyctl/ssh-sftp-find/)	 - The SFTP FIND command lists files (from an optional root directory) on a remote VM.
* [get](/docs/flyctl/ssh-sftp-get/)	 - The SFTP GET retrieves a file from a remote VM.
* [shell](/docs/flyctl/ssh-sftp-shell/)	 - The SFTP SHELL command brings up an interactive SFTP session to fetch and push files from/to a VM.

## Options

~~~
  -h, --help   help for sftp
~~~

## Global Options

~~~
  -t, --access-token string   Fly API Access Token
      --debug                 Print additional logs and traces
      --verbose               Verbose output
~~~

## See Also

* [flyctl ssh](/docs/flyctl/ssh/)	 - Use SSH to login to or run commands on VMs

