# autofill

auto fill provider for [`pyclavis`](https://github.com/kr-g/pyclavis)


# contribution

you want to contribute and merge your own provider, and autofill data.

just clone, add your own data in separate folder, provide a `.pygg` file,
and send a pull/ merge request.


# structure

have a look at the `pyclavis` folder and there -> `autofill.pygg`


# generic auto-fill

there are 3 generic auto-fill provider available which should fit the most commonly scenarios.

|name|remark|
|---|---|
|`generic`|the most common case where user and password is on a single html page|
|`generic-2-steps`|a provider where user and password are entered on 2 different html pages, with an intermediate server-call between the 2 html pages. can be custominzed by parameter `NDELAY` |
|`generic-pass-only`|a provider where only a password is required to log-in, such as e.g. local Fritz.Box router|


# related toolset

[`pygitgrab`](https://github.com/kr-g/pygitgrab)

