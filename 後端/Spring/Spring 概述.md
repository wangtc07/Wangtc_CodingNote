1. Spring 是輕量級的開源 JavaEE 框架
2. 可以解決應用開發的複雜性
3. 有兩個核心部分
   1. IOC
      - 控制反轉: 把創建對象的過程交給 Spring 進行管理
   2. Aop
      - 面向切面: 不修改源代碼，進行功能增強
4. 特點
   1. 方便解耦，簡化開發
   2. Aop 編程的支持
   3. 方便程序的測試
   4. 方便和其他框架整合
   5. 降低 JavaEE API 的使用難度
   6. 方便進行事務的操作

---

# Spring Framework 安裝

[開始在 Mac 上開發 Spring boot | Austin's notes](https://blog.gclin.org/2019/06/18/start-spring-boot-development-on-mac/)
[Spring 在 mac 下的配置以及简单使用\_王朝虎的博客-CSDN 博客](https://blog.csdn.net/wangchaohx/article/details/52791790)
[idea(mac) 版本导入 spring-framework-5 源码\_我是老才的博客-CSDN 博客](https://blog.csdn.net/zfshi2010/article/details/104447496)
[9. 安裝 Spring Boot](https://docs.spring.io/spring-boot/docs/1.0.x/reference/html/getting-started-installing-spring-boot.html)

1. spring.io
2. Spring Framework
3. GitHub
4. Spring Framework Artifacts
5. downloading a distribution
   1. https://repo.spring.io

- release
  - org
    - springframework
      - spring
        **Repository Path:**
        複製到`.io/`後面

1. 取得壓縮檔
   https://repo.spring.io/webapp/#/artifacts/browse/tree/General/libs-release-local/org/springframework/spring/5.0.2.RELEASE

測試

1. 創建新 java project
   ![](https://i.imgur.com/7DlBD0D.png)
2. 導入 Spring5 相關 jar 包 (Core Container)
   ![](https://i.imgur.com/PSTGrFu.png)
   ![](https://i.imgur.com/rsekfg9.png)

3. 創建普通類和方法
   ![](https://i.imgur.com/2CLBFMX.png)
4. 創建 Spring 配置文件，在配置文件 配置創建的對象 1. new >> ![](https://i.imgur.com/IWyFqOE.png) 2. 配置 User 對象
   class=java 檔路徑位置
   ![](https://i.imgur.com/UNYIUlM.png)

5. 進行測試代碼編寫 1. 加載 spring 配置文件 2. 獲取配置創建的對象
   ![](https://i.imgur.com/M4yf2rf.png)
