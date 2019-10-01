# Spring MVCStudy

## :book: Learning DispatcherServlet initialization & service process

##### Spring Version: 4.3.3
##### Build tool: Gradle

#### *[스프링 MVC Reference 번역 정보](documents/spring-framework-reference/ko/spring-mvc-translated-version.md)*

### Study Curriculum

#### [DispatcherServlet 의 초기화 과정](documents/description/DispatcherServlet-Initiation.md)

#### [BeanFactory 의 초기화 과정](documents/description/BeanFactory-Initiation.md)

###### Servlet 의 초기화

###### DispatcherServlet 의 상속구조
- ApplicationContext 구성 및 초기화
    - ApplicationContext 생성: FrameworkServlet#createWebApplicationContext()
    - BeanFactory 생성: AbstractRefreshableApplicationContext#refreshBeanFactory()
    - BeanDefinition 로딩: AnnotationConfigWebApplicationContext:loadBeanDefinitions()
    - BeanPostProcessor 등록: PostProcessorRegistrationDelegate:registerBeanPostProcessors()
    - SingletonBean (전처리)미리 등록: DefaultListableBeanFactory:preInstantiateSingletons()
    
#### [웹 요청의 처리 과정](documents/description/DispatcherServlet-Processing.md)

###### 


### 클래스 별 설정 데이터 정보

##### [DispatcherServlet](documents/class-config/DispatcherServlet-config.md)
##### [BeanFactory](documents/class-config/BeanFactory-config.md)
##### [RequestMappingHandlerMapping](documents/class-config/RequestMappingHandlerMapping-config.md)
##### [RequestMappingHandlerAdapter](documents/class-config/RequestMappingHandlerAdapter-config.md)

### 스터디 진도
#### [첫번째 모임](documents/time-topic/2019-10-1-SpringMVC-why.md)
