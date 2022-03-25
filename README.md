# egcs24 updates

#### 10:40pm ADT, March 24 2022

>uth:vc0 api:vc41 ui:vc62  
>Fixed Issues #1 and #2
>There is is still doubt on the bit inverter code. Either the packet decoder or the frame decoder might have a problem still.
>The UI auto-refreshes incomplete Rx messages.
>Relaxed the throttling a bit. 

#### 12pm ADT, March 19 2022

>uth:vc0 api:vc4 ui:vc3  
>Updated the API to stop purging data. This deleted the data accumulated so far.
Trying to understand what causes issue #1
>
>This will trigger an accumulation of data and at some point I will have to purge it again. By then hepefully the bug would have been identified and fixed

