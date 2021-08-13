### EAF System Monitor
<p align="center">
  <img width="800" src="./screenshot.png">
</p>

System Monitor application for the [Emacs Application Framework](https://github.com/emacs-eaf/emacs-application-framework).

### Load application

```Elisp
(add-to-list 'load-path "~/.emacs.d/site-lisp/eaf-system-monitor/")
(require 'eaf-system-monitor)
```

### Dependency List

| Package       | Description                                                        |
| :--------     | :------                                                            |
| python-psutil | Retrieving information on running processes and system utilization |
