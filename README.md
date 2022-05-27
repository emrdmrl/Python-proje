# [Python-proje](www.patika.dev)
 m = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
mnew = []
def flatten(n):
    for i in n:
        if isinstance(i, list):
            flatten(i)
        else:
            mnew.append(i)
flatten(m)
print(mnew)


l =[[1, 2], [3, 4], [5, 6, 7]]
l=l[::-1]

for i in range(len(l)):
    (l[i])=(l[i])[::-1]
print(l)