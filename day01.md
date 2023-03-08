```
@Slf4j
@SpringBootApplication
public class ReggieApplication {
    public static void main(String[] args) {
        SpringApplication.run(ReggieApplication.class,args);
        log.info("Springboot started");
    }

}
```
```
@Configuration
public class MvcWebConfig extends WebMvcConfigurationSupport {
    @Override
    protected void addResourceHandlers(ResourceHandlerRegistry registry) {
        registry.addResourceHandler("/backend/**").addResourceLocations("classpath:/backend/");
    }
}
```
```
const fs = require('fs');
fs.readFile('/Users/mengjiayu/Desktop/1.js','utf-8',function(err,dataStr){
    console.log(err);
    console.log(dataStr);
})
```
