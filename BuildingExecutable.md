You need some additional gems to build the RXData Editor executable from the source code. You can install them typing this on the command line:

```
  [sudo] gem install rake rubyscript2exe
```

Then just call the build task:

```
  rake build
```

The output executable is called rxdataed in Linux and rxdataed.exe in
Windows. I don't know how it is called in Mac, I believe it's rxdataed.app.
By default, rubyscript2exe will call the Linux executable as rxdataed\_linux,
but the Rakefile will rename it. You can run this executable in any computer
without installing Ruby or the required gems. It would be nice if someone make
an installer for Windows or Debian and RPM packages for Linux. I don't know how
Mac applications are distributeds.