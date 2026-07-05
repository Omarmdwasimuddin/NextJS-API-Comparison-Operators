## NextJS API---> Comparison Operators

###
![](https://imgur.com/ZOkkBkC.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    equals: 50000,
                }
            }
        });
```
---

###
![](https://imgur.com/AJMQq7G.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    not: 50000,
                }
            }
        });
```
---

###
![](https://imgur.com/YtPtsLd.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    lt: 50000,
                }
            }
        });
```
---
