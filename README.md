## π νλ‘μ νΈ κ°μ(Introduce Project)
### Reactive
* λ¦¬μ‘νΈ Sequelize CRUD μμ  μλλ€.
* React C.R.U.D(Create, Read, Update, Delete) Template(Feat. Sequelize)

## π·οΈ κΈ°λ₯(Function)

1. [Sequelize-CREATE](#Sequelize-CREATE)
2. [Sequelize-READ](#Sequelize-READ)
3. [Sequelize-UPDATE](#Sequelize-UPDATE)
4. [Sequelize-DELETE](#Sequelize-DELETE)

#### Sequelize-CREATE
#### Sequelize-READ
#### Sequelize-UPDATE
#### Sequelize-DELETE

## π‘ Sequelize-CLI μ¬μ©λ²

1. μνΌλΌμ΄μ¦μ μλ§κ² νλ‘μ νΈ λλ ν λ¦¬λ₯Ό κ΅¬μ±ν©λλ€.
   1. `npx sequelize init`

2. λ°μ΄ν°λ² μ΄μ€(Database) μμ±ν©λλ€.
   1. `npx sequelize db:create --env development`

3. νμ΄λΈ(Table) μμ±ν©λλ€.
   1. `npx sequelize model:generate --name νμ΄λΈλͺ --attributes μμ±1:νμ,μμ±2:νμ,μμ±3:νμ`
   2. `npx sequelize model:generate --name Board --attributes index:integer,title:string contents:string,date:string`
   3. `Output`:`../model/νμ΄λΈλͺ.js`

4. λ§μ΄κ·Έλ μ΄μ μ μ©ν©λλ€.
   1. `npx sequelize db:migrate`
   2. `Output`:`../migrations/'yyyyMMddHHmmSS-create-νμ΄λΈλͺ.js'`

5. κΈ°μ΄(Seed) λ°μ΄ν° μμ±ν©λλ€.
   1. `npx sequelize seed:generate --name μ΄κΈ° λ°μ΄ν° μ΄λ¦`
   2. `npx sequelize seed:generate --name initialData`
   3. `Output`:`../seeders/'yyyyMMddHHmmSS-μ΄κΈ° λ°μ΄ν° μ΄λ¦.js'`

6. κΈ°μ΄ λ°μ΄ν° νμΌ μ μ©, μ½μν©λλ€.
   1. `npx sequelize db:seed:all  --debug`

### index.js

* `Sequelize`λ₯Ό μ¬μ©νκΈ° μν μ€μ μΌλ‘ μΆμ .

## π λΉκ³ (Remark)

### νλ‘μ νΈ μ€ν

> `npm run start`

### API μλ² μ€ν

> `npm start server`

### ν¨ν€μ§ λ³΅μ(Packages Recovery)

* `npm install`
* [packages.json](./package.json)