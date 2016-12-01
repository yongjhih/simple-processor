# simple-processor

## development

```java
interface Listener<T> {
   call(T t);
}
```

```java
// Generated SimpleListener<T>
SimpleListener<T> implements Listener<T> {
  @Override public void call(T t) {}
}
```
