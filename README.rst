Requires::

  watchdog==0.6.0


Run::

  python -m SimpleHTTPServer
  watchmedo shell-command --patterns="*.less" --command='lessc style.less --source-map style.css'
