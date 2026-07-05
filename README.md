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

###
![](https://imgur.com/UzJRVWf.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    gte: 50000,
                }
            }
        });
```
---

###
![](https://imgur.com/Vd2OAwk.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    in: [35000, 70000],
                }
            }
        });
```
---

###
![](https://imgur.com/4nQZC1D.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    notIn: [35000, 70000],
                }
            }
        });
```
---

###
![](https://imgur.com/UtJ5Ptx.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                salary: {
                    gt: 35000, lt: 70000,
                }
            }
        });
```
---

###
![](https://imgur.com/9u0Z8Gn.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                name: {
                    contains: "Wasim",
                }
            }
        });
```
---

###
![](https://imgur.com/bkOWQ68.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                name: {
                    startsWith: "I",
                }
            }
        });
```
---

###
![](https://imgur.com/9VO88Jj.png)

```bash
const readData = await prisma.employee.findMany({
            where: {
                name: {
                    endsWith: "I",
                }
            }
        });
```
---
