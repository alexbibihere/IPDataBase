# IPDataBase
通过传入的ip获取所在城市


# 接口
根据IP查询城市或地区的接口是IpHelper类中的findRegionByIp接口，说明如下：

```
/**
 * 静态方法，传入ip地址，返回ip地址所在城市或地区
 * @param ip    IP地址，例：58.30.15.255
 * @return  返回IP地址所在城市或地区，例：北京市
 */
public static String findRegionByIp(String ip)
```

# example
```
public void example() throws Exception {
    String ip = "58.30.15.255";
    String region = IpHelper.findRegionByIp(ip);
    System.out.println(region);
}
```


