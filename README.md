# Spring-Framwork-basic


BeanFactory và ApplicationContext interface là 2 interface đại diện cho Spring IoC container. BeanFactory là root interface dùng để thao tác với Spring container, nó cung cấp những tính năng cơ bản để quản lý bean trong ứng dụng.

ApplicationContext interface là một sub-interface của BeanFactory, vì vậy nó cung cấp tất cả các tính năng trong BeanFactory ngoài ra nó còn cung cấp một số tính năng quan trọng khác như:

Bean instantiation/wiring
Automatic BeanPostProcessor registration
Automatic BeanFactoryPostProcessor registration
Convenient MessageSource access (for i18n)
ApplicationEvent publication
