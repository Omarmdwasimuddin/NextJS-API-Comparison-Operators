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
