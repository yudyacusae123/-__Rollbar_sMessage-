# -__Rollbar_sMessage-
; Rollbar_Send's helper functions ; Parameters ....:  $__Rollbar_sMessage         - [Required] The message to be sent. This should contain any useful debugging info that will help you debug. ;                   $__Rollbar_sMessageSummary  - [Optional] A string that will be used as the title of the Item occurrences will be grouped into. Max length 255 characters. If omitted, Rollbar will determine this on the backend. _Rollbar_SendDebug("This is an debug message. If you received this, you were successful!", "Debug Message")
