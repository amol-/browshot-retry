Browsershot Support
===================

Usage::

    from browshow import SHOTS_BROWSERS, ScreenshotThread

    shotthread = ScreenshotThread('http://www.google.com', '/tmp/test.png', SHOTS_BROWSERS['chrome'])
    shotthread.start()
    shotthread.join()
