PROJECT (NavigationService)

SET(QT_SERVICE_PATH /etc/systemd/system)
SET(QT_APP_PATH /usr/local/bin)
INSTALL(FILES navigation.service DESTINATION ${QT_SERVICE_PATH})

