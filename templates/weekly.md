Prev: [[<% moment().subtract(1, "weeks").format("YYYY-MM-[w]ww") %>]] <== This Week ==>  Next: [[<% moment().add(1, "weeks").format("YYYY-MM-[w]ww") %>]]

# <% tp.date.now("YYYY-MM-[w]ww") %>


##### Monday
![[<% moment().startOf('isoWeek').format("YYYY-MM-DD-dddd") %>#Outcomes]]

##### Tues
![[<% moment().startOf('isoWeek').add(1,'days').format("YYYY-MM-DD-dddd") %>#Outcomes]]

##### Weds
![[<% moment().startOf('isoWeek').add(2,'days').format("YYYY-MM-DD-dddd") %>#Outcomes]]

##### Thurs
![[<% moment().startOf('isoWeek').add(3,'days').format("YYYY-MM-DD-dddd") %>#Outcomes]]

##### Fri
![[<% moment().startOf('isoWeek').add(4,'days').format("YYYY-MM-DD-dddd") %>#Outcomes]]

##### Sat
![[<% moment().startOf('isoWeek').add(5,'days').format("YYYY-MM-DD-dddd") %>#Outcomes]]

##### Sun
![[<% moment().startOf('isoWeek').add(6,'days').format("YYYY-MM-DD-dddd") %>#Outcomes]]


## Outcomes
