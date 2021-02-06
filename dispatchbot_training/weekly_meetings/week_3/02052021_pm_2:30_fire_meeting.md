# **02/05/2021 2:30pm <br> <br> Fire Meeting🔥**

**Ideas:**

@Fox and @Chad - joined
  * apt time and pickup time was major concern

@Fox
  * Thinks something is wrong with the code. DispatchBot only has a priority flag set for pickup or dropoff. It needs the option for both though
  * There are keys for pickup, dropoff, and apt
  * The drive time is determined by how the flag is set
  * There were some brokers that put a focus more on pickup or dropoff 

@Josh
  * Brought up timezone issues and how this might cause discrepencies between Logisticare's API and how we are processing the data

@Amanda - joined: 2:50pm
  * apt time gets set as pickup time
  * Default as pickup is none, so conditional logic is not being ran and gets skipped
  * Bug is on lines 247-256 roughly bc her edition of the code was old
  * Use `orgainizational setting` query

&nbsp;

**Need:**

All set at the moment!

&nbsp;

**Questions:**

> Why did the previous programmmers only set a priority flag for one or the other and not set the default to update the pickup and dropoff keys according to the data we called from the API? ✅
>
> **`Answer`**: @Fox 
>
> &nbsp; &nbsp; &nbsp; &nbsp; There were some brokers that put a focus more on pickup or dropoff 

&nbsp;

**Action Items:**

No actions item needed!