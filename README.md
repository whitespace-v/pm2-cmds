
# Getting started 

### Start daemon

#### 1. Install pm2
```
npm i pm2 -g
```
#### 2. Start daemon client
```
pm2 --name Client start npm -- start
```
#### 3. Start daemon server
```
pm2 --name Server start npm -- run dev
```
#### 3. Save
```
pm2 save
```
#### Display table
```
pm2 list
```
#### Display monitor
```
pm2 monit
```
#### Display logs
```
pm2 logs
```