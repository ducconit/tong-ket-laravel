# Chinh phục Laravel

### Design pattern
##### Không nên dùng
- Repository pattern(tầng model): làm rối code hơn, thừa 1 số file(BaseRepositoryInterface,BaseRepositoryAbstract,...) bởi abstract Model đã có các cái này cho chúng ta rồi, còn bạn nói là để làm ngắn code lại? Hãy tạo các traits hoặc ghi thẳng vào `model` của bạn các scope đều đó chẳng phải dễ dàng hơn sao?
- Builder Pattern hay Manager Pattern: Pattern này rất hữu ích cho việc module hóa hệ thống. Laravel đã cung cấp sắn `\Illuminate/Support/Manager.php` việc của bạn chỉ cần extend từ class này thôi
.. updating..
