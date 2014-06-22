untimely
=================

Make time measurements with ease!


Usage
-----------------

    from untimely import TimeMeasurement
    from time     import sleep

    with TimeMeasurement() as t:
      sleep(3)
      print("DONE!")

    print(t.length)

