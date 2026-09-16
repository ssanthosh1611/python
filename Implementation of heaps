import heapq
jobs=[]
heapq.heappush(jobs,(-3,"Job A"))
heapq.heappush(jobs,(-5,"Job B"))
heapq.heappush(jobs,(-1,"Job C"))
heapq.heappush(jobs,(-4,"Job D"))
print("Jobs in Heap Order:")
for priority,job in jobs:
    print(job,"Priority:",-priority)
print("\n Highest Priority Jobs:",jobs[0][1])
print("priority:",-jobs[0][0])
priority,job=heapq.heappop(jobs)
print("\n Processed Job:",job)
print("Priority:",-priority)
print("\n Remaining Jobs:")
for priority,job in jobs:
    print(job,"Priority:",-priority)
