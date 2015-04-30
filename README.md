Random number server application
================================

A gen_server that provides uniform real and integer random numbers
using random:uniform_s().  This allows any process to get random
numbers without having to worry about calling random:seed to
initialize a seed in the process dictionary.

Add this to a project's rebar.config to use:

````
{deps, [
    {rnd, ".*", {git, "https://github.com/tommay/erlang-rnd.git"}}
	]}.
````
