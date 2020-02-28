# Blue Prism Mainframe Interface

Blue Prism has a built-interface to expose the API functionality with a wide mainframe emulator.

## Spying Elements:

  The mainframe session supported within Blue Prism expose an API that allows Blue Prism to Blue Prism provides a grid tool to allow you to quickly spy regions on the mainframe screen. For details on how to use this see the “Guide to Using the Blue Prism Mainframe Spy”.
  Once an element has been captured it is possible to copy and paste that element within 
Application Modeller. This allows you to create new elements quickly and simply rename them and set the appropriate X, Y coordinates. This can be useful if you already know the screen 
coordinates of the field you want to interact with or the coordinates are displayed on the 
mainframe screen.
  When spying fields within a mainframe session it is not always possible to determine where the field ends. The following screen shot displays a mainframe screen where the field sizes are known.Here you can easily specify the field widths for all the fields as it is indicated by the green line. On the following mainframe screen the input fields are not easily identifiable.If we are inputting text to the field, we can use the cursor and type text until we reach the end of the field i.e. populate all the available space in all the fields on the screen.However, if we are reading from the screen we won’t know the sizes of the fields. For example where does the residential address field end? In these situations, we identify the field to be the maximum width available on the screen to avoid the risk of cutting off the end of field data as below.

## Trimming Data:

  Whether the field sizes are known or not what is essential when reading from a mainframe session is that you trim all data once you have read it from the screen. This will remove any leading or trailing spaces. Typically, you will read from the screen using one read stage then trim all data using a Multiple Calculation stage before casting any dates or numbers.
