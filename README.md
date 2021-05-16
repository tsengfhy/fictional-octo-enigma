<h1 align="center">JDK</h1>

## Version

1.8.0_212

## Usage

- 通过 =======> 搜索入口
- 通过序号字符搜索标签（eg. ⑴、①……）

## Note

- 在并发下，若操作分主次，可主操作使用无条件操作（a = b），次操作使用CAS加自旋，如此在出现竞争时，次操作必将失败以保证主操作的成功
- LockSupport.park(this) 后可通过 LockSupport.unpark(thread) 或中断唤醒