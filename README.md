# php容器和依赖注入

**基于php的反射机制实现，访问要实例化的类内部获取构造参数，用递归处理要需要的依赖类，完成自动注入**

test.php中的company是上层类，依赖department和group类

container.php中通过的MyContainer的build方法可以直接实例化company类，并完成注入
