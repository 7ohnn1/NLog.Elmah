# Funnel all NLog into Elmah
[![AppVeyor](https://img.shields.io/appveyor/ci/7ohnn1/nlog-elmahh/master.svg)](https://ci.appveyor.com/project/7ohnn1/nlog-Elmah/branch/master)

ELMAH target for NLog

Extensions to [NLog](https://github.com/NLog/NLog/) & Forked from [NLog.Elmah](https://github.com/NLog/NLog.Elmah/)

##Notes
This is specific to my use :
- Source shows Full path, Classname, Method
- Appends "NLog" in front of type where the "error" is funnelled by NLog
- Adds user whenever possible (I'm using it more like debug / tracking)
