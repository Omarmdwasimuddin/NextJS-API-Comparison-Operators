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
![](https://imgur.com/AJMQq7G.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    notIn: [50000],
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

###
![](https://imgur.com/L0hLqrM.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    lte: 50000,
                }
            }
        });
```
---

###
![](https://imgur.com/zz7gdnT.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    gt: 50000,
                }
            }
        });
```
---
