# TZLicense

## Introduction 

一个方便对消息进行流量控制的组件

## Installation

add jar file to library

## Usage

there are two kinds of licenses

- PerSecondCountLicense
- SumCountLicense


### PerSecondCountLicense
 
#### Initialization
```java
TZLicense tzLicense = new PerSecondCountLicense(100);
tzLicense.tryAcquire()
```

#### reset
```java
tzLicense.reset();
```

### PerSecondCountLicense

```java
TZLicense tzLicense = new PerSecondCountLicense(5);
tzLicense.tryAcquire()
```

#### reset
```java
tzLicense.reset();
```

