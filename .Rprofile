# Set hook to be run when Defaults is attached
setHook(packageEvent("Defaults", "attach"),
          function(...) { setDefaults(q, save="no"); useDefaults(q) })
# add Defaults to the default packages loaded on startup
old <- getOption("defaultPackages");
options(defaultPackages = c(old, "Defaults"))
