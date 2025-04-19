# 📑 Yêu cầu chi tiết dự án ZylPeloXStore (ZPX) - VERSION 1.0

**Mã dự án:** ZPX-ECOM
**Ngày khởi tạo:** 10-02-2023
**Ngày cập nhật:** 14-04-2025
**Tác giả:** phamtiendungcw
**Phiên bản:** 1.0

## 1. 🎯 TỔNG QUAN DỰ ÁN

### 1.1. Mục tiêu

Xây dựng nền tảng cửa hàng bán lẻ trực tuyến ZylPeloXStore (ZPX) với kiến trúc hiện đại, tích hợp đầy đủ tính năng quản lý từ đầu đến cuối, đáp ứng nhu cầu kinh doanh đa kênh với khả năng mở rộng cao và bảo trì dễ dàng.

> **_Chú thích:_** _Dự án nhằm tạo ra một nền tảng eCommerce toàn diện, không chỉ đáp ứng nhu cầu hiện tại mà còn có khả năng mở rộng trong tương lai._

### 1.2. Phạm vi

- **Hệ thống quản lý bán hàng và tồn kho toàn diện**: Theo dõi sản phẩm, đơn hàng và tồn kho theo thời gian thực
- **Nền tảng eCommerce đầy đủ chức năng**: Trải nghiệm mua sắm trực tuyến liền mạch cho khách hàng
- **Tích hợp thanh toán và vận chuyển**: Hỗ trợ nhiều phương thức thanh toán và đối tác vận chuyển
- **Hệ thống CRM và quản lý khách hàng**: Quản lý thông tin và tương tác với khách hàng
- **Dashboard quản trị và báo cáo**: Công cụ phân tích dữ liệu và báo cáo toàn diện

> **_Chú thích:_** _Dự án sẽ bao gồm cả backend và frontend, API được thiết kế để dễ dàng mở rộng và tích hợp với các hệ thống khác._

### 1.3. Giới hạn

- **Khối lượng dữ liệu và truy cập**: Hệ thống được thiết kế để xử lý khối lượng dữ liệu và người dùng từ trung bình đến lớn (lên đến 100,000 sản phẩm, 50,000 người dùng đồng thời)
- **Thời gian phát triển dự kiến**: 6-9 tháng cho phiên bản MVP, với lộ trình phát triển tiếp theo được chia thành các giai đoạn
- **Quy mô nhóm phát triển**: Yêu cầu đội ngũ 5-8 người bao gồm backend, frontend, QA và DevOps

> **_Chú thích:_** _Các giới hạn được xác định để đặt kỳ vọng rõ ràng và đảm bảo việc lập kế hoạch tài nguyên phù hợp._

## 2. 🛍️ TÍNH NĂNG HỆ THỐNG

### 2.1. Quản lý Catalog

- **Sản phẩm và biến thể**
  - Tạo/sửa/xóa/khôi phục sản phẩm với giao diện quản trị trực quan
  - Quản lý biến thể không giới hạn (màu sắc, kích thước, v.v.)
  - Thông số kỹ thuật và mô tả đa dạng với định dạng phong phú (rich text)
  - Giá cả và thuế có thể cấu hình theo khu vực

> **_Chú thích:_** _Hệ thống sẽ hỗ trợ sản phẩm đơn giản và sản phẩm có nhiều biến thể. Mỗi biến thể có thể có giá, mã SKU và tồn kho riêng._

- **Danh mục**
  - Cấu trúc danh mục đa cấp không giới hạn độ sâu
  - Sản phẩm có thể thuộc nhiều danh mục khác nhau
  - SEO tối ưu cho từng danh mục (meta title, description, URL)

> **_Chú thích:_** _Danh mục sẽ được thiết kế với hiệu suất cao, đảm bảo thời gian phản hồi nhanh ngay cả khi có hàng nghìn sản phẩm._

- **Quản lý phương tiện**
  - Thư viện hình ảnh/video tập trung với bộ lọc và tìm kiếm
  - Tối ưu hóa hình ảnh tự động (nén, thay đổi kích thước, chuyển đổi định dạng)
  - Hỗ trợ CDN để tăng tốc tải trang

> **_Chú thích:_** _Hệ thống sẽ sử dụng dịch vụ lưu trữ đám mây cho media để đảm bảo hiệu suất và khả năng mở rộng._

### 2.2. Quản lý Khách hàng

- **Hồ sơ khách hàng chi tiết**: Thông tin cá nhân, lịch sử mua hàng, sở thích
- **Phân nhóm khách hàng và tags**: Phân loại khách hàng để tiếp thị và phân tích
- **Lịch sử mua hàng và tương tác**: Theo dõi toàn bộ hành trình khách hàng
- **Hệ thống đánh giá và điểm thưởng**: Khuyến khích khách hàng quay lại
- **Quản lý địa chỉ giao hàng/thanh toán**: Hỗ trợ nhiều địa chỉ cho mỗi khách hàng

> **_Chú thích:_** _Module này sẽ tích hợp với hệ thống CRM để cung cấp cái nhìn 360 độ về khách hàng._

### 2.3. Quản lý Kho hàng

- **Theo dõi tồn kho theo thời gian thực**: Cập nhật số lượng tồn kho ngay khi có thay đổi
- **Nhập/xuất kho với lịch sử đầy đủ**: Theo dõi mọi thay đổi tồn kho
- **Quản lý nhiều kho và vị trí**: Hỗ trợ mô hình kinh doanh phân tán
- **Cảnh báo tồn kho thấp**: Thông báo khi sản phẩm gần hết hàng
- **Báo cáo tồn kho và giá trị hàng hóa**: Phân tích giá trị tồn kho theo thời gian

> **_Chú thích:_** _Hệ thống kho sẽ được thiết kế để xử lý cả quy trình thủ công và tự động, tích hợp với các thiết bị quét mã vạch nếu cần._

### 2.4. Quản lý Vận chuyển

- **Tích hợp nhiều đối tác vận chuyển**: API-based integration với các đơn vị vận chuyển phổ biến
- **Ma trận phí vận chuyển tùy chỉnh**: Xác định phí vận chuyển dựa trên khu vực, trọng lượng, giá trị
- **Theo dõi trạng thái vận chuyển**: Cập nhật theo thời gian thực về tình trạng đơn hàng
- **In ấn vận đơn và đóng gói**: Tự động tạo và in vận đơn
- **Xử lý hoàn hàng**: Quy trình hoàn hàng và hoàn tiền đầy đủ

> **_Chú thích:_** _Module này sẽ cung cấp API mở để dễ dàng tích hợp với các nhà cung cấp dịch vụ vận chuyển mới._

### 2.5. Quản lý Thanh toán

- **Đa dạng phương thức thanh toán**: Hỗ trợ thẻ tín dụng, chuyển khoản, ví điện tử, COD
- **Xử lý thanh toán an toàn**: Tuân thủ PCI DSS và tiêu chuẩn bảo mật
- **Lịch sử giao dịch và hoàn tiền**: Theo dõi đầy đủ các giao dịch tài chính
- **Hỗ trợ trả góp và thanh toán một phần**: Linh hoạt trong các phương thức thanh toán
- **Xác thực thanh toán**: Tích hợp 3D Secure và các phương thức xác thực hiện đại

> **_Chú thích:_** _Hệ thống thanh toán sẽ được thiết kế với tính mở rộng cao, cho phép thêm mới các cổng thanh toán dễ dàng._

### 2.6. Quản lý Đơn hàng

- **Quy trình xử lý đơn hàng linh hoạt**: Tùy chỉnh quy trình theo nhu cầu kinh doanh
- **Trạng thái đơn hàng tùy chỉnh**: Tạo và quản lý các trạng thái đơn hàng theo yêu cầu
- **Lịch sử thay đổi đơn hàng**: Theo dõi mọi thay đổi trong vòng đời đơn hàng
- **Đơn hàng dự trữ và đặt trước**: Hỗ trợ đặt hàng trước khi sản phẩm có sẵn
- **Bán hàng chéo và bán thêm**: Đề xuất sản phẩm liên quan khi đặt hàng

> **_Chú thích:_** _Module đơn hàng là trung tâm của hệ thống, tích hợp với tất cả các module khác để cung cấp trải nghiệm xuyên suốt._

### 2.7. Khuyến mãi & Giảm giá

- **Mã giảm giá và voucher**: Tạo và quản lý các mã giảm giá với nhiều điều kiện
- **Chương trình khuyến mãi theo thời gian**: Lên lịch khuyến mãi tự động
- **Giảm giá theo nhóm khách hàng**: Giá đặc biệt cho khách hàng VIP
- **Giảm giá theo số lượng**: Giảm giá khi mua số lượng lớn
- **Quà tặng và sản phẩm kèm theo**: Thêm sản phẩm quà tặng vào đơn hàng

> **_Chú thích:_** _Hệ thống khuyến mãi được thiết kế để hỗ trợ các chiến dịch marketing phức tạp với nhiều quy tắc kết hợp._

### 2.8. Nội dung & Marketing

- **Blog và bài viết**: Hệ thống quản lý nội dung tích hợp
- **Landing page và banner quảng cáo**: Tạo và quản lý các trang đích cho chiến dịch
- **SEO tools và metadata**: Tối ưu hóa nội dung cho công cụ tìm kiếm
- **Email marketing templates**: Tạo và gửi email marketing từ hệ thống
- **Đánh giá và bình luận sản phẩm**: Thu thập phản hồi của khách hàng

> **_Chú thích:_** _Module này sẽ cung cấp các công cụ để quản lý nội dung và tối ưu hóa SEO một cách hiệu quả._

### 2.9. Nhân viên & Phân quyền

- **Quản lý người dùng và vai trò**: Tạo và quản lý tài khoản nhân viên
- **Phân quyền chi tiết theo chức năng**: Kiểm soát quyền truy cập đến cấp độ hành động
- **Theo dõi hoạt động người dùng**: Ghi lại mọi thay đổi và hành động trong hệ thống
- **Xác thực hai lớp**: Tăng cường bảo mật cho tài khoản quan trọng
- **Giới hạn theo IP và thời gian**: Kiểm soát thời gian và địa điểm truy cập

> **_Chú thích:_** _Hệ thống phân quyền sẽ được thiết kế để linh hoạt và chi tiết, cho phép tạo các vai trò tùy chỉnh theo nhu cầu cụ thể của doanh nghiệp._

## 3. 🛠️ KIẾN TRÚC & CÔNG NGHỆ

### 3.1. Stack Công nghệ

- **Backend**: ASP.NET Core 6 (với khả năng nâng cấp lên phiên bản mới nhất)
- **Frontend**: Angular 16 (với tên project "zpx-ui" theo chuẩn kebab-case)
- **Database**: SQL Server (hỗ trợ phân vùng cho hiệu suất cao)
- **Cache**: Redis + HybridCache (kết hợp memory cache và distributed cache)
- **Search**: Elasticsearch (tùy chọn, để tối ưu hóa tìm kiếm)
- **Message Queue**: RabbitMQ (tùy chọn, cho xử lý bất đồng bộ)

> **_Chú thích:_** _Stack công nghệ được chọn để đảm bảo hiệu suất cao, bảo mật và khả năng mở rộng. Các công nghệ này có cộng đồng lớn và hỗ trợ dài hạn._

### 3.2. Kiến trúc Phần mềm

- **Clean Architecture**
  - Domain-centric: Đặt logic nghiệp vụ ở trung tâm
  - Tách biệt các mối quan tâm: Domain, Application, Infrastructure, Presentation
  - Dependency Rule: Các phụ thuộc chỉ hướng vào trong (domain core)

> **_Chú thích:_** _Clean Architecture giúp tạo ra code dễ bảo trì, dễ test và độc lập với các framework, database hay UI._

- **Domain-Driven Design**
  - Aggregate Roots: Xác định ranh giới nhất quán của dữ liệu
  - Bounded Context: Phân chia hệ thống thành các ngữ cảnh có ý nghĩa
  - Entity và Value Objects: Phân biệt rõ ràng giữa các đối tượng có danh tính và không có danh tính

> **_Chú thích:_** _DDD giúp mô hình hóa các domain phức tạp và đảm bảo rằng code phản ánh đúng business rules._

- **Modular Monolith**
  - Khả năng chuyển đổi sang Microservices sau này
  - Module separation: Tách biệt rõ ràng giữa các module
  - Shared kernel: Chia sẻ các khái niệm chung giữa các module

> **_Chú thích:_** _Modular Monolith là lựa chọn cân bằng giữa tính đơn giản của monolith và tính linh hoạt của microservices._

### 3.3. Design Patterns

- **CQRS với MediatR**
  - Commands (Write): Thay đổi trạng thái hệ thống
  - Queries (Read): Truy vấn dữ liệu, không thay đổi trạng thái
  - Notifications (Events): Thông báo sự kiện đến các handler khác nhau

> **_Chú thích:_** _CQRS giúp tách biệt logic đọc và ghi, cho phép tối ưu hóa riêng cho mỗi loại, đặc biệt hữu ích cho hệ thống có tỉ lệ đọc/ghi chênh lệch._

- **Repository & Specification Pattern**
  - Generic Repository: Interface chung cho việc truy xuất dữ liệu
  - Specification abstraction: Đóng gói logic truy vấn

> **_Chú thích:_** _Repository pattern giúp tách biệt logic truy cập dữ liệu khỏi domain logic, trong khi Specification pattern giúp tái sử dụng và kết hợp các điều kiện truy vấn._

- **Domain Events**
  - Event publishing: Phát hành sự kiện khi có thay đổi trong domain
  - Event handling: Xử lý các tác động phụ do sự kiện gây ra

> **_Chú thích:_** _Domain Events cho phép các phần khác nhau của hệ thống phản ứng với những thay đổi mà không cần kết nối trực tiếp, giúp giảm sự phụ thuộc._

### 3.4. Packages & Libraries

#### 3.4.1. Backend (.NET)

- **MediatR**: Triển khai CQRS và xử lý sự kiện
- **FluentValidation**: Validation dựa trên fluent interface
- **AutoMapper**: Mapping giữa các đối tượng
- **FluentResults**: Xử lý kết quả với nhiều trạng thái
- **Serilog**: Logging có cấu trúc
- **Ardalis.Specification**: Triển khai pattern Specification
- **EFCore.BulkExtensions**: Tối ưu các thao tác hàng loạt
- **BCrypt.Net-Next**: Mã hóa mật khẩu
- **Swashbuckle**: Tài liệu API (Swagger)

> **_Chú thích:_** _Các thư viện được chọn dựa trên độ tin cậy, hiệu suất và mức độ hỗ trợ tốt từ cộng đồng._

#### 3.4.2. Frontend (Angular)

- **Angular Material**: Thành phần UI
- **NgRx**: Quản lý state
- **RxJS**: Lập trình reactive
- **Angular Flex Layout**: Layout phản hồi
- **NgxTranslate**: Đa ngôn ngữ

> **_Chú thích:_** _Các thư viện frontend được chọn để cung cấp trải nghiệm người dùng nhất quán và hiệu suất cao._

## 4. 🧩 THIẾT KẾ DOMAIN

### 4.1. Entities & Base Classes

- **BaseEntity**

    ```csharp
    public abstract class BaseEntity
    {
        public Guid Id { get; protected set; }
    }
    ```

> **_Chú thích:_** _BaseEntity là lớp cơ sở cho tất cả các entity, định nghĩa một khóa chính dạng GUID._

- **BaseAuditableEntity**

    ```csharp
    public abstract class BaseAuditableEntity : BaseEntity
    {
        public DateTime CreatedAt { get; set; }
        public string CreatedBy { get; set; }
        public DateTime? LastModifiedAt { get; set; }
        public string LastModifiedBy { get; set; }
        public bool IsDeleted { get; set; }
        public DateTime? DeletedAt { get; set; }
        public string DeletedBy { get; set; }
    }
    ```

> **_Chú thích:_** _BaseAuditableEntity mở rộng từ BaseEntity, thêm các trường theo dõi thời gian tạo, cập nhật và xóa mềm (soft delete)._

### 4.2. Aggregate Roots

- **Product Aggregate**
  - Product (Aggregate Root): Thông tin cơ bản về sản phẩm
  - ProductVariant: Các biến thể của sản phẩm (màu sắc, kích cỡ,...)
  - ProductAttribute: Thuộc tính sản phẩm (như chất liệu, xuất xứ,...)
  - ProductImage: Hình ảnh sản phẩm
  - ProductSpecification: Thông số kỹ thuật chi tiết

> **_Chú thích:_** _Product Aggregate chứa tất cả các thông tin liên quan đến sản phẩm và được quản lý như một đơn vị nhất quán._

- **Order Aggregate**
  - Order (Aggregate Root): Thông tin đơn hàng
  - OrderItem: Các sản phẩm trong đơn hàng
  - OrderStatus: Trạng thái của đơn hàng
  - OrderPayment: Thông tin thanh toán
  - ShippingDetails: Chi tiết vận chuyển

> **_Chú thích:_** _Order Aggregate đại diện cho toàn bộ quá trình đặt hàng, từ sản phẩm đến thanh toán và vận chuyển._

- **Customer Aggregate**
  - Customer (Aggregate Root): Thông tin khách hàng
  - Address: Địa chỉ giao hàng/thanh toán
  - PaymentMethod: Phương thức thanh toán lưu trữ
  - CustomerGroup: Nhóm khách hàng
  - CustomerNote: Ghi chú về khách hàng

> **_Chú thích:_** _Customer Aggregate quản lý tất cả thông tin liên quan đến khách hàng và tương tác của họ với hệ thống._

- **Inventory Aggregate**
  - Inventory (Aggregate Root): Quản lý tồn kho
  - StockItem: Mặt hàng trong kho
  - StockTransaction: Giao dịch nhập/xuất kho
  - Warehouse: Thông tin kho hàng
  - Location: Vị trí trong kho

> **_Chú thích:_** _Inventory Aggregate quản lý tất cả các khía cạnh của việc theo dõi tồn kho._

- **Promotion Aggregate**
  - Promotion (Aggregate Root): Thông tin khuyến mãi
  - DiscountRule: Quy tắc giảm giá
  - Coupon: Mã giảm giá
  - PromotionUsage: Lịch sử sử dụng khuyến mãi

> **_Chú thích:_** _Promotion Aggregate quản lý các chiến dịch khuyến mãi và việc áp dụng chúng._

### 4.3. Junction/Intermediate Entities

- **ProductCategory** (many-to-many): Kết nối Product và Category
- **ProductTag** (many-to-many): Kết nối Product và Tag
- **OrderDiscount** (many-to-many): Kết nối Order và Discount
- **CustomerPromotion** (many-to-many): Kết nối Customer và Promotion

> **_Chú thích:_** _Các entity này quản lý mối quan hệ nhiều-nhiều giữa các entity chính._

### 4.4. Value Objects

- **Money**: Giá trị tiền tệ (Amount + Currency)
- **Address**: Thông tin địa chỉ
- **DateRange**: Khoảng thời gian
- **ContactInformation**: Thông tin liên lạc

> **_Chú thích:_** _Value Objects là các đối tượng không có nhận dạng riêng, được định nghĩa bởi các thuộc tính và bất biến (immutable)._

### 4.5. Domain Services

- **OrderProcessingService**: Xử lý logic phức tạp liên quan đến đơn hàng
- **PricingService**: Tính toán giá dựa trên nhiều yếu tố
- **InventoryService**: Quản lý logic cập nhật tồn kho
- **PaymentProcessingService**: Xử lý giao dịch thanh toán

> **_Chú thích:_** _Domain Services chứa logic nghiệp vụ phức tạp không thuộc về một entity cụ thể nào._

### 4.6. Domain Events

- **OrderPlacedEvent**: Phát ra khi đơn hàng được đặt
- **PaymentReceivedEvent**: Phát ra khi nhận được thanh toán
- **ProductOutOfStockEvent**: Phát ra khi sản phẩm hết hàng
- **CustomerRegisteredEvent**: Phát ra khi khách hàng đăng ký mới

> **_Chú thích:_** _Domain Events cho phép các phần khác nhau của hệ thống phản ứng với những thay đổi quan trọng._

## 5. 📁 CẤU TRÚC SOLUTION

```plaintext
📁 ZylPeloXStore
 ├── 📁 Core
 │   ├── 📁 ZPX.Domain                 // Logic nghiệp vụ cốt lõi
 │   │   ├── 📁 Entities               // Các entity cơ bản
 │   │   ├── 📁 Aggregates             // Các aggregate roots
 │   │   │   ├── 📁 Product
 │   │   │   ├── 📁 Order
 │   │   │   ├── 📁 Customer
 │   │   │   └── 📁 Inventory
 │   │   ├── 📁 JunctionEntities       // Entity mối quan hệ nhiều-nhiều
 │   │   ├── 📁 ValueObjects           // Value objects
 │   │   ├── 📁 Events                 // Domain events
 │   │   ├── 📁 Exceptions             // Domain exceptions
 │   │   └── 📁 Services               // Domain services
 │   │
 │   └── 📁 ZPX.Application            // Logic ứng dụng
 │       ├── 📁 Common
 │       │   ├── 📁 Behaviors          // Pipeline behaviors (validation, logging)
 │       │   ├── 📁 Specifications     // Query specifications
 │       │   └── 📁 Exceptions         // Application exceptions
 │       ├── 📁 Contracts
 │       │   ├── 📁 Persistence        // Persistence interfaces
 │       │   │   └── 📁 Repositories   // Repository interfaces
 │       │   ├── 📁 Infrastructure     // Infrastructure interfaces
 │       │   └── 📁 Identity           // Identity interfaces
 │       ├── 📁 Features               // CQRS features
 │       │   ├── 📁 Products           // Product-related commands/queries
 │       │   ├── 📁 Orders             // Order-related commands/queries
 │       │   ├── 📁 Customers          // Customer-related commands/queries
 │       │   └── 📁 Inventory          // Inventory-related commands/queries
 │       └── 📁 EventHandlers          // Domain event handlers
 │
 ├── 📁 Infrastructure
 │   ├── 📁 ZPX.Infrastructure         // Dịch vụ cơ sở hạ tầng
 │   │   ├── 📁 Cache                  // Caching implementation
 │   │   ├── 📁 Email                  // Email service
 │   │   ├── 📁 FileStorage            // File storage service
 │   │   ├── 📁 MessageBroker          // Message broker integration
 │   │   └── 📁 ThirdPartyServices     // Third-party integrations
 │   │
 │   ├── 📁 ZPX.Persistence            // Truy cập dữ liệu
 │   │   ├── 📁 Configurations         // EF Core configurations
 │   │   ├── 📁 Repositories           // Repository implementations
 │   │   └── 📁 Migrations             // Database migrations
 │   │
 │   └── 📁 ZPX.Identity               // Xác thực và phân quyền
 │       ├── 📁 Models                 // Identity models
 │       ├── 📁 Services               // Identity services
 │       └── 📁 Configurations         // Identity configurations
 │
 ├── 📁 Presentation
 │   ├── 📁 ZPX.Server                 // Web API
 │   │   ├── 📁 Controllers            // API controllers
 │   │   ├── 📁 Filters                // Action filters
 │   │   ├── 📁 Middleware             // Custom middleware
 │   │   └── 📁 Configurations         // API configurations
 │   │
 │   └── 📁 zpx-ui                     // Angular frontend (đổi từ ZPX.WebClient)
 │       ├── 📁 src
 │       │   ├── 📁 app
 │       │   │   ├── 📁 core           // Core functionality
 │       │   │   ├── 📁 shared         // Shared components
 │       │   │   └── 📁 features       // Feature modules
 │       │   ├── 📁 assets             // Static assets
 │       │   └── 📁 environments       // Environment configurations
 │       └── 📁 angular.json           // Angular configuration
 │
 ├── 📁 Shared                         // Shared code
 │   └── 📁 ZPX.Shared                 // Shared utilities and DTOs
 │       ├── 📁 Constants              // Shared constants
 │       ├── 📁 Extensions             // Extension methods
 │       └── 📁 Utilities              // Utility classes
 │
 └── 📁 Tests                          // Tests
     ├── 📁 ZPX.UnitTests              // Unit tests
     ├── 📁 ZPX.IntegrationTests       // Integration tests
     └── 📁 ZPX.E2ETests               // End-to-end tests
```

> **_Chú thích:_** _Cấu trúc solution tuân theo nguyên tắc của Clean Architecture, với các layer rõ ràng và sự phụ thuộc đi từ ngoài vào trong. Dự án frontend được đổi tên từ ZPX.WebClient thành zpx-ui để tuân theo quy ước đặt tên của Angular._

## 6. 📝 APPLICATION LAYER DETAILS

### 6.1. CQRS Implementation

- **Commands** (Write operations)
  - CreateProductCommand: Tạo sản phẩm mới
  - UpdateProductCommand: Cập nhật thông tin sản phẩm
  - DeleteProductCommand: Xóa sản phẩm (soft delete)

> **_Chú thích:_** _Commands đại diện cho các thao tác thay đổi trạng thái hệ thống, trả về kết quả thành công/thất bại._

- **Queries** (Read operations)
  - GetProductsQuery: Lấy danh sách sản phẩm có phân trang
  - GetProductByIdQuery: Lấy chi tiết sản phẩm theo ID
  - SearchProductsQuery: Tìm kiếm sản phẩm với các điều kiện phức tạp

> **_Chú thích:_** _Queries chỉ đọc dữ liệu, không thay đổi trạng thái và được tối ưu hóa cho hiệu suất đọc._

- **Command/Query Handlers**
  - CreateProductCommandHandler: Xử lý logic tạo sản phẩm
  - GetProductsQueryHandler: Xử lý logic lấy danh sách sản phẩm
  - etc.

> **_Chú thích:_** _Mỗi command/query có một handler tương ứng, giúp tách biệt logic xử lý và dễ dàng thêm middleware._

### 6.2. DTOs & Mapping

- **Request DTOs**
  - CreateProductRequest: DTO cho yêu cầu tạo sản phẩm
  - UpdateProductRequest: DTO cho yêu cầu cập nhật sản phẩm
  - etc.

> **_Chú thích:_** _Request DTOs định nghĩa dữ liệu đầu vào từ client, thường được sử dụng làm tham số cho Commands._

- **Response DTOs**
  - ProductDto: DTO trả về thông tin cơ bản về sản phẩm
  - ProductDetailDto: DTO trả về thông tin chi tiết về sản phẩm
  - OrderDto: DTO trả về thông tin về đơn hàng
  - etc.

> **_Chú thích:_** _Response DTOs định nghĩa dữ liệu trả về cho client, tách biệt với domain model nội bộ._

- **Mapping Profiles**
  - ProductMappingProfile: Cấu hình mapping giữa Product và ProductDto
  - OrderMappingProfile: Cấu hình mapping giữa Order và OrderDto
  - etc.

> **_Chú thích:_** _Mapping Profiles định nghĩa cách chuyển đổi giữa domain models và DTOs, sử dụng AutoMapper._

### 6.3. Validation

- **Validators**
  - CreateProductValidator: Xác thực dữ liệu tạo sản phẩm
  - UpdateProductValidator: Xác thực dữ liệu cập nhật sản phẩm
  - etc.

> **_Chú thích:_** _Validators sử dụng FluentValidation để định nghĩa các quy tắc xác thực cho dữ liệu đầu vào._

- **Validation Behavior**
  - Implement MediatR Pipeline Behavior for validation

> **_Chú thích:_** _Validation Behavior đảm bảo tất cả các requests được xác thực trước khi xử lý, tập trung hóa logic validation._

### 6.4. Application Services

- **Email Service**: Gửi email thông báo, xác nhận đơn hàng
- **File Storage Service**: Upload và quản lý hình ảnh sản phẩm
- **Cache Service**: Caching dữ liệu thường xuyên truy cập
- **Message Service**: Gửi thông báo qua message queue

> **_Chú thích:_** _Application Services cung cấp các chức năng hỗ trợ cho application layer, thường là wrapper cho các dịch vụ cơ sở hạ tầng._

## 7. 🌐 API DESIGN & ENDPOINTS

### 7.1. RESTful API Principles

- **Resource-based URLs**: URLs đại diện cho resources, không phải actions
- **HTTP methods**: Sử dụng GET, POST, PUT, DELETE đúng cách
- **Proper status codes**: Trả về HTTP status codes phù hợp (200, 201, 400, 404, 500, etc.)
- **Paging, filtering, sorting**: Cung cấp khả năng phân trang, lọc và sắp xếp dữ liệu

> **_Chú thích:_** _API được thiết kế theo nguyên tắc RESTful để đảm bảo tính nhất quán và dễ sử dụng._

### 7.2. API Versioning

- **URL-based versioning**: `/api/v1/products`

> **_Chú thích:_** _Versioning giúp đảm bảo tính tương thích ngược khi API thay đổi._

### 7.3. API Documentation

- **Swagger/OpenAPI integration**: Tài liệu API tự động
- **Documented examples**: Ví dụ request/response
- **API changelog**: Theo dõi thay đổi giữa các phiên bản API

> **_Chú thích:_** _Tài liệu API chi tiết giúp các nhà phát triển dễ dàng tích hợp với hệ thống._

### 7.4. Controller Examples

```csharp
[ApiController]
[Route("api/v1/[controller]")]
public class ProductsController : ControllerBase
{
    private readonly IMediator _mediator;

    public ProductsController(IMediator mediator)
    {
        _mediator = mediator;
    }

    [HttpGet]
    public async Task<ActionResult<PaginatedList<ProductDto>>> GetProducts([FromQuery] GetProductsQuery query)
    {
        var result = await _mediator.Send(query);
        return Ok(result);
    }

    [HttpGet("{id}")]
    public async Task<ActionResult<ProductDetailDto>> GetProductById(Guid id)
    {
        var result = await _mediator.Send(new GetProductByIdQuery(id));
        return result.Match<ActionResult>(
            success => Ok(success),
            error => NotFound()
        );
    }

    [HttpPost]
    public async Task<ActionResult<ProductDto>> CreateProduct(CreateProductRequest request)
    {
        var result = await _mediator.Send(new CreateProductCommand(request));
        return result.Match<ActionResult>(
            success => CreatedAtAction(nameof(GetProductById), new { id = success.Id }, success),
            error => BadRequest(error.Reasons)
        );
    }
}
```

> **_Chú thích:_** _Controller sử dụng MediatR để chuyển tiếp requests đến các handlers tương ứng, giúp controllers nhẹ và chỉ tập trung vào việc xử lý HTTP._

## 8. 💾 DATABASE & DATA ACCESS

### 8.1. Database Schema Overview

- **Product-related tables**: Products, ProductVariants, Categories, etc.
- **Order-related tables**: Orders, OrderItems, OrderStatuses, etc.
- **Customer-related tables**: Customers, Addresses, CustomerGroups, etc.
- **Inventory tables**: Inventories, StockItems, Warehouses, etc.
- **Junction tables**: ProductCategories, ProductTags, etc.

> **_Chú thích:_** _Schema được thiết kế để cân bằng giữa chuẩn hóa (để giảm dư thừa) và denormalization (để cải thiện hiệu suất đọc)._

### 8.2. Entity Framework Core Configuration

```csharp
public class ProductConfiguration : IEntityTypeConfiguration<Product>
{
    public void Configure(EntityTypeBuilder<Product> builder)
    {
        builder.ToTable("Products");
        builder.HasKey(p => p.Id);

        builder.Property(p => p.Name)
            .IsRequired()
            .HasMaxLength(200);

        builder.Property(p => p.Description)
            .HasMaxLength(4000);

        builder.HasMany(p => p.Variants)
            .WithOne(v => v.Product)
            .HasForeignKey(v => v.ProductId)
            .OnDelete(DeleteBehavior.Cascade);

        builder.HasQueryFilter(p => !p.IsDeleted); // Soft delete
    }
}
```

> **_Chú thích:_** _Entity Framework configurations được tách riêng để giữ cho domain models sạch và tập trung vào business logic._

### 8.3. Migration Strategy

- **Code-First approach**: Tạo database schema từ C# classes
- **Incremental migrations**: Thêm migrations cho mỗi thay đổi schema
- **Schema versioning**: Giữ phiên bản của schema để dễ dàng rollback
- **Data seeding for lookup tables**: Khởi tạo dữ liệu cho các bảng lookup

> **_Chú thích:_** _Chiến lược migration đảm bảo database schema có thể theo dõi được thay đổi và dễ dàng triển khai trên nhiều môi trường._

### 8.4. Performance Considerations

- **Proper indexing**: Tạo indexes cho các cột thường xuyên tìm kiếm
- **Batch operations with BulkExtensions**: Sử dụng bulk operations cho thao tác hàng loạt
- **Optimization for read operations (CQRS)**: Tách biệt database đọc và ghi nếu cần
- **N+1 problem prevention**: Sử dụng Include và eager loading phù hợp

> **_Chú thích:_** _Hiệu suất database là ưu tiên hàng đầu, đặc biệt khi hệ thống mở rộng với lượng dữ liệu lớn._

## 9. 🖥️ FRONTEND ARCHITECTURE

### 9.1. Angular Structure

- **Core Module**: Services, guards và components bắt buộc
- **Shared Module**: Components, directives và pipes dùng chung
- **Feature Modules**: Modules theo tính năng, lazy-loaded
- **Component Architecture**: Smart và presentational components

> **_Chú thích:_** _Cấu trúc Angular tuân theo Angular Style Guide, tổ chức code theo tính năng và khả năng tái sử dụng._

### 9.2. State Management

- **NgRx Store for complex state**: Quản lý state phức tạp toàn cầu
- **Services with RxJS for simple state**: Quản lý state đơn giản với services
- **Local component state where appropriate**: State cục bộ cho components

> **_Chú thích:_** _State management strategy phụ thuộc vào độ phức tạp của state, tránh over engineering cho các state đơn giản._

### 9.3. UI Components

- **Angular Material components as base**: Sử dụng Material Design
- **Custom components extended from Material**: Mở rộng Material components
- **Responsive design with Flex Layout**: Layout linh hoạt trên mọi thiết bị

> **_Chú thích:_** _UI components được thiết kế để nhất quán và tái sử dụng, với Material Design làm nền tảng._

### 9.4. Routing & Navigation

- **Feature-based routing**: Routes được tổ chức theo tính năng
- **Route guards for authorization**: Kiểm soát truy cập vào routes
- **Lazy-loading for performance**: Tải modules khi cần

> **_Chú thích:_** _Routing strategy tận dụng lazy-loading để cải thiện thời gian tải ban đầu và phân tách rõ ràng giữa các tính năng._

### 9.5. Internationalization

- **Multi-language support with NgxTranslate**: Hỗ trợ nhiều ngôn ngữ
- **Currency and date formatting based on locale**: Định dạng tiền tệ và ngày tháng theo locale
- **RTL support for applicable languages**: Hỗ trợ ngôn ngữ viết từ phải sang trái

> **_Chú thích:_** _I18n được tích hợp từ đầu để đảm bảo ứng dụng có thể dễ dàng hỗ trợ nhiều ngôn ngữ và khu vực._

## 10. 🛑 ERROR HANDLING & LOGGING

### 10.1. Exception Handling

- **Custom domain exceptions with "Zpx" prefix**: ZpxNotFoundException, ZpxValidationException, etc.
- **Global exception middleware**: Xử lý lỗi tập trung
- **Structured error responses**: Format lỗi nhất quán cho client

> **_Chú thích:_** _Exception handling được thiết kế để cung cấp thông tin hữu ích cho developers và người dùng, đồng thời bảo vệ thông tin nhạy cảm._

### 10.2. Logging Strategy

- **Structured logging with Serilog**: Logs có cấu trúc để dễ dàng tìm kiếm và phân tích
- **Log levels (Debug, Info, Warning, Error, Fatal)**: Phân loại logs theo mức độ nghiêm trọng
- **Log enrichment with context data**: Thêm context data vào mỗi log entry
- **Log storage and rotation**: Lưu trữ và xoay vòng logs để quản lý dung lượng

> **_Chú thích:_** _Logging là một phần quan trọng của hệ thống, giúp ghi lại hoạt động và phát hiện sự cố._

### 10.3. Monitoring

- **Health checks**: Kiểm tra sức khỏe hệ thống
- **Application metrics**: Đo lường hiệu suất ứng dụng
- **Performance counters**: Theo dõi các chỉ số hiệu suất hệ thống
- **API usage statistics**: Thống kê sử dụng API

> **_Chú thích:_** _Monitoring giúp phát hiện sớm các vấn đề và cung cấp insights về hiệu suất hệ thống._

## 11. 🔒 SECURITY CONSIDERATIONS

### 11.1. Authentication & Authorization

- **JWT-based authentication**: Xác thực dựa trên JSON Web Tokens
- **Role-based authorization**: Phân quyền dựa trên vai trò
- **Policy-based access control**: Kiểm soát truy cập dựa trên policies
- **Refresh token strategy**: Cơ chế làm mới token

> **_Chú thích:_** _Authentication và authorization được thiết kế để bảo vệ tài nguyên và đảm bảo người dùng chỉ truy cập được vào tài nguyên được phép._

### 11.2. Data Protection

- **HTTPS everywhere**: Mã hóa tất cả giao tiếp
- **Data encryption for sensitive info**: Mã hóa thông tin nhạy cảm trong database
- **Input validation and sanitization**: Xác thực và làm sạch input
- **CSRF protection**: Bảo vệ chống lại tấn công Cross-Site Request Forgery

> **_Chú thích:_** _Data protection là ưu tiên hàng đầu, đặc biệt là thông tin cá nhân và tài chính của khách hàng._

### 11.3. API Security

- **Rate limiting**: Giới hạn số lượng requests
- **Request validation**: Xác thực tất cả requests
- **API keys for external systems**: Khóa API cho hệ thống bên ngoài
- **CORS configuration**: Cấu hình Cross-Origin Resource Sharing

> **_Chú thích:_** _API security đảm bảo API chỉ được sử dụng bởi các clients hợp lệ và không bị lạm dụng._

## 12. 📦 CACHING STRATEGY

### 12.1. Cache Levels

- **Memory cache (first level)**: Cache trong bộ nhớ cho dữ liệu truy cập thường xuyên
- **Distributed cache with Redis (second level)**: Cache phân tán cho môi trường nhiều instances
- **Browser caching for static assets**: Cache trên trình duyệt cho tài nguyên tĩnh

> **_Chú thích:_** _Multi-level caching giúp tối ưu hóa hiệu suất ở mỗi layer của hệ thống._

### 12.2. Cache Invalidation

- **Time-based expiration**: Cache hết hạn sau một khoảng thời gian
- **Event-based invalidation**: Cache được làm mới khi có sự kiện liên quan
- **Cache dependencies**: Cache phụ thuộc vào các cache khác

> **_Chú thích:_** _Cache invalidation đảm bảo dữ liệu cache luôn được cập nhật và nhất quán với dữ liệu gốc._

### 12.3. Cacheable Resources

- **Product catalog data**: Dữ liệu catalog sản phẩm
- **User preferences**: Tùy chọn người dùng
- **Lookup data**: Dữ liệu tham khảo ít thay đổi
- **Session data**: Dữ liệu phiên

> **_Chú thích:_** _Việc xác định rõ những resource nào nên được cache giúp tối ưu hóa hiệu suất và tránh lãng phí bộ nhớ._

## 13. ✅ TESTING APPROACH

### 13.1. Unit Testing

- **Domain logic tests**: Kiểm tra logic domain
- **Application handlers tests**: Kiểm tra handlers
- **Services tests**: Kiểm tra services

> **_Chú thích:_** _Unit tests tập trung vào việc kiểm tra các đơn vị code nhỏ một cách cô lập._

### 13.2. Integration Testing

- **Repository tests**: Kiểm tra truy cập dữ liệu
- **API endpoint tests**: Kiểm tra endpoints API
- **Database integration tests**: Kiểm tra tích hợp database

> **_Chú thích:_** _Integration tests kiểm tra tương tác giữa các thành phần của hệ thống._

### 13.3. E2E Testing

- **Critical user flows**: Kiểm tra các luồng nghiệp vụ quan trọng
- **UI/UX testing**: Kiểm tra giao diện người dùng
- **Performance testing**: Kiểm tra hiệu suất

> **_Chú thích:_** _E2E tests kiểm tra toàn bộ hệ thống từ góc nhìn của người dùng cuối._

### 13.4. Testing Tools

- **xUnit for unit/integration tests**: Framework testing cho .NET
- **Moq for mocking**: Library để tạo mock objects
- **Cypress for E2E tests**: Framework testing cho web applications

> **_Chú thích:_** _Các công cụ testing được chọn dựa trên sự phổ biến, hiệu suất và khả năng tích hợp với CI/CD._

## 14. 🚀 DEPLOYMENT & DEVOPS

### 14.1. CI/CD Pipeline

- **Automated builds with GitHub Actions**: Tự động hóa quá trình build
- **Automated testing**: Chạy tests tự động
- **Static code analysis**: Phân tích code tĩnh
- **Deployment automation**: Tự động hóa triển khai

> **_Chú thích:_** _CI/CD pipeline đảm bảo code được kiểm tra và triển khai một cách nhất quán và đáng tin cậy._

### 14.2. Environments

- **Development**: Môi trường phát triển
- **Testing**: Môi trường kiểm thử
- **Staging**: Môi trường pre-production
- **Production**: Môi trường sản phẩm

> **_Chú thích:_** _Multiple environments đảm bảo code được kiểm tra kỹ lưỡng trước khi đến production._

### 14.3. Deployment Strategy

- **Docker containerization**: Đóng gói ứng dụng trong containers
- **Azure App Service deployment**: Triển khai lên Azure App Service
- **Blue-green deployment (zero downtime)**: Triển khai không gián đoạn

> **_Chú thích:_** _Deployment strategy tập trung vào zero downtime và khả năng rollback nhanh chóng._

## 15. 📅 ROADMAP & PHASING

### 15.1. Phase 1: MVP (Month 1-3)

- **Core product catalog**: Quản lý sản phẩm cơ bản
- **Basic order management**: Quản lý đơn hàng đơn giản
- **Customer accounts**: Đăng ký và quản lý tài khoản
- **Admin dashboard**: Dashboard quản trị cơ bản
- **Payment integration (1-2 providers)**: Tích hợp thanh toán với 1-2 nhà cung cấp

> **_Chú thích:_** _Phase 1 tập trung vào việc xây dựng các tính năng cốt lõi để ra mắt sản phẩm sớm và nhận feedback._

### 15.2. Phase 2: Enhanced Features (Month 4-6)

- **Inventory management**: Quản lý kho hàng
- **Advanced product search**: Tìm kiếm sản phẩm nâng cao
- **Promotions & discounts**: Hệ thống khuyến mãi và giảm giá
- **Customer reviews**: Đánh giá sản phẩm
- **Expanded payment options**: Mở rộng các tùy chọn thanh toán

> **_Chú thích:_** _Phase 2 mở rộng chức năng dựa trên feedback từ Phase 1 và thêm các tính năng nâng cao._

### 15.3. Phase 3: Advanced Features (Month 7-9)

- **Analytics & reporting**: Phân tích và báo cáo
- **Marketing tools**: Công cụ marketing
- **Multi-vendor support (optional)**: Hỗ trợ nhiều nhà cung cấp
- **Mobile app (optional)**: Ứng dụng di động
- **API for third-parties**: API cho bên thứ ba

> **_Chú thích:_** _Phase 3 thêm các tính năng nâng cao và mở rộng hệ sinh thái của sản phẩm._

## 16. 📏 CODING STANDARDS & QUALITY

### 16.1. Naming Conventions

- **DTO Request**: `Create[EntityName]Request`, `Update[EntityName]Request`
- **Specifications**: `[EntityName]Spec.cs`
- **Custom Exceptions**: `Zpx[ExceptionName]`
- **Project Prefix**: `ZPX`

> **_Chú thích:_** _Naming conventions đảm bảo code nhất quán và dễ đọc trên toàn bộ dự án._

### 16.2. Code Quality Tools

- **SonarLint/SonarQube**: Phân tích code quality
- **StyleCop**: Kiểm tra code style
- **EditorConfig**: Cấu hình editor nhất quán
- **Code quality gates in CI/CD**: Kiểm tra quality trong CI/CD

> **_Chú thích:_** _Code quality tools giúp duy trì chất lượng code cao và nhất quán trên toàn bộ dự án._

### 16.3. Documentation

- **Code documentation (XML comments)**: Tài liệu code với XML comments
- **Architecture documentation**: Tài liệu kiến trúc
- **API documentation**: Tài liệu API
- **User guides**: Hướng dẫn người dùng

> **_Chú thích:_** _Documentation là một phần quan trọng của dự án, giúp các developers mới dễ dàng tiếp cận và hiểu code._

### 16.4. Development Practices

- **Code reviews**: Đánh giá code trước khi merge
- **Pull request workflow**: Quy trình pull request
- **Feature branch strategy**: Branch theo tính năng
- **Test-driven development (when applicable)**: Phát triển hướng test khi phù hợp

> **_Chú thích:_** _Development practices đảm bảo code chất lượng cao và giảm thiểu bugs._

---

## APPENDIX A: RESOURCE REQUIREMENTS

### A.1. Development Team

- **1 Tech Lead / Architect**: Chịu trách nhiệm về kiến trúc tổng thể
- **3-4 Backend Developers**: Phát triển backend
- **2 Frontend Developers**: Phát triển frontend
- **1 QA Engineer**: Đảm bảo chất lượng
- **1 DevOps Engineer (part-time)**: Quản lý deployment và CI/CD

> **_Chú thích:_** _Team size được thiết kế để cân bằng giữa tốc độ phát triển và quản lý hiệu quả._

### A.2. Infrastructure

- **Development environments**: Môi trường phát triển cho mỗi developer
- **Test/QA environment**: Môi trường kiểm thử
- **Staging environment**: Môi trường pre-production
- **Production environment**: Môi trường sản phẩm
- **CI/CD pipeline**: Pipeline tự động hóa
- **Source control repository**: Repository quản lý source code

> **_Chú thích:_** _Infrastructure được thiết kế để hỗ trợ phát triển liên tục và deployment nhanh chóng._

### A.3. Estimated Timeline

- **Planning & Setup**: 2-3 weeks
- **MVP Development**: 2-3 months
- **Testing & Refinement**: 1 month
- **Enhanced Features**: 3 months
- **Advanced Features**: 3 months

> **_Chú thích:_** _Timeline là ước tính ban đầu và có thể điều chỉnh dựa trên tiến độ thực tế và feedback._

---

**Phê duyệt:**

| Vai trò       | Tên            | Chữ ký | Ngày |
| ------------- | -------------- | ------ | ---- |
| Người yêu cầu | phamtiendungcw | ✓      |      |
| Quản lý dự án | phamtiendungcw | ✓      |      |
| Kiến trúc sư  | phamtiendungcw | ✓      |      |

---

## 🗃️ Thiết kế Database cho ZylPeloXStore (ZPX)

> **Ngày hiện tại:** 2025-04-15 11:00:01
> **Người dùng:** phamtiendungcw

## 📋 Tổng quan các bảng

Dưới đây là các bảng dữ liệu được thiết kế cho ZPX eCommerce platform:

1. **Identity Tables** - Quản lý người dùng và xác thực
2. **Core eCommerce Tables** - Sản phẩm, danh mục, đơn hàng
3. **Customer Management Tables** - Khách hàng, địa chỉ
4. **Inventory & Stock Tables** - Quản lý hàng tồn kho
5. **Review & Rating Tables** - Đánh giá sản phẩm
6. **Marketing Tables** - Khuyến mãi, mã giảm giá

## 🔑 Identity Tables

### 1. AspNetUsers (Bảng Identity mặc định)

| Column Name          | Data Type      | Constraints | Description             |
| -------------------- | -------------- | ----------- | ----------------------- |
| Id                   | nvarchar(450)  | PK          | Định danh người dùng    |
| UserName             | nvarchar(256)  |             | Tên đăng nhập           |
| NormalizedUserName   | nvarchar(256)  |             | Tên đăng nhập chuẩn hóa |
| Email                | nvarchar(256)  |             | Email                   |
| NormalizedEmail      | nvarchar(256)  |             | Email chuẩn hóa         |
| EmailConfirmed       | bit            |             | Email đã xác nhận       |
| PasswordHash         | nvarchar(max)  |             | Mật khẩu đã hash        |
| SecurityStamp        | nvarchar(max)  |             | Dùng cho bảo mật        |
| ConcurrencyStamp     | nvarchar(max)  |             | Kiểm soát đồng thời     |
| PhoneNumber          | nvarchar(max)  |             | Số điện thoại           |
| PhoneNumberConfirmed | bit            |             | SĐT đã xác nhận         |
| TwoFactorEnabled     | bit            |             | Xác thực 2 yếu tố       |
| LockoutEnd           | datetimeoffset |             | Thời gian khóa hết hạn  |
| LockoutEnabled       | bit            |             | Khóa tài khoản          |
| AccessFailedCount    | int            |             | Số lần đăng nhập sai    |
| FirstName            | nvarchar(100)  |             | Tên                     |
| LastName             | nvarchar(100)  |             | Họ                      |
| ProfilePictureUrl    | nvarchar(500)  |             | URL ảnh đại diện        |

### 2. AspNetRoles

| Column Name      | Data Type     | Constraints | Description           |
| ---------------- | ------------- | ----------- | --------------------- |
| Id               | nvarchar(450) | PK          | Định danh vai trò     |
| Name             | nvarchar(256) |             | Tên vai trò           |
| NormalizedName   | nvarchar(256) |             | Tên vai trò chuẩn hóa |
| ConcurrencyStamp | nvarchar(max) |             | Kiểm soát đồng thời   |

### 3. AspNetUserRoles

| Column Name | Data Type     | Constraints | Description   |
| ----------- | ------------- | ----------- | ------------- |
| UserId      | nvarchar(450) | PK, FK      | ID người dùng |
| RoleId      | nvarchar(450) | PK, FK      | ID vai trò    |

### 4. AspNetUserClaims, AspNetRoleClaims, AspNetUserLogins, AspNetUserTokens

\*(Các bảng Identity khác theo chuẩn)\_

## 🛒 Core eCommerce Tables

### 5. Products

| Column Name           | Data Type        | Constraints          | Description                |
| --------------------- | ---------------- | -------------------- | -------------------------- |
| Id                    | uniqueidentifier | PK                   | Định danh sản phẩm         |
| Name                  | nvarchar(200)    | NOT NULL             | Tên sản phẩm               |
| Description           | nvarchar(max)    |                      | Mô tả sản phẩm             |
| ShortDescription      | nvarchar(500)    |                      | Mô tả ngắn                 |
| Price                 | decimal(18,2)    | NOT NULL             | Giá                        |
| OldPrice              | decimal(18,2)    |                      | Giá cũ (khi giảm giá)      |
| SpecialPrice          | decimal(18,2)    |                      | Giá đặc biệt               |
| SpecialPriceStartDate | datetime2        |                      | Ngày bắt đầu giá đặc biệt  |
| SpecialPriceEndDate   | datetime2        |                      | Ngày kết thúc giá đặc biệt |
| StockQuantity         | int              | NOT NULL, DEFAULT(0) | Số lượng tồn kho           |
| Weight                | decimal(18,4)    |                      | Trọng lượng                |
| Length                | decimal(18,4)    |                      | Chiều dài                  |
| Width                 | decimal(18,4)    |                      | Chiều rộng                 |
| Height                | decimal(18,4)    |                      | Chiều cao                  |
| Sku                   | nvarchar(100)    |                      | Stock Keeping Unit         |
| Gtin                  | nvarchar(100)    |                      | Global Trade Item Number   |
| CategoryId            | uniqueidentifier | FK                   | ID danh mục                |
| BrandId               | uniqueidentifier | FK                   | ID thương hiệu             |
| IsActive              | bit              | NOT NULL, DEFAULT(1) | Trạng thái kích hoạt       |
| IsFeatured            | bit              | NOT NULL, DEFAULT(0) | Sản phẩm nổi bật           |
| CreatedAt             | datetime2        | NOT NULL             | Ngày tạo                   |
| CreatedBy             | nvarchar(450)    |                      | Người tạo                  |
| ModifiedAt            | datetime2        |                      | Ngày sửa đổi               |
| ModifiedBy            | nvarchar(450)    |                      | Người sửa đổi              |

### 6. ProductImages

| Column Name  | Data Type        | Constraints          | Description      |
| ------------ | ---------------- | -------------------- | ---------------- |
| Id           | uniqueidentifier | PK                   | Định danh ảnh    |
| ProductId    | uniqueidentifier | FK, NOT NULL         | ID sản phẩm      |
| ImageUrl     | nvarchar(500)    | NOT NULL             | URL ảnh          |
| AltText      | nvarchar(200)    |                      | Văn bản thay thế |
| DisplayOrder | int              | NOT NULL, DEFAULT(0) | Thứ tự hiển thị  |
| IsMain       | bit              | NOT NULL, DEFAULT(0) | Ảnh chính        |
| CreatedAt    | datetime2        | NOT NULL             | Ngày tạo         |
| CreatedBy    | nvarchar(450)    |                      | Người tạo        |

### 7. ProductAttributes

| Column Name    | Data Type        | Constraints          | Description          |
| -------------- | ---------------- | -------------------- | -------------------- |
| Id             | uniqueidentifier | PK                   | Định danh thuộc tính |
| ProductId      | uniqueidentifier | FK, NOT NULL         | ID sản phẩm          |
| AttributeName  | nvarchar(100)    | NOT NULL             | Tên thuộc tính       |
| AttributeValue | nvarchar(500)    | NOT NULL             | Giá trị thuộc tính   |
| DisplayOrder   | int              | NOT NULL, DEFAULT(0) | Thứ tự hiển thị      |
| CreatedAt      | datetime2        | NOT NULL             | Ngày tạo             |
| CreatedBy      | nvarchar(450)    |                      | Người tạo            |

### 8. Categories

| Column Name     | Data Type        | Constraints          | Description          |
| --------------- | ---------------- | -------------------- | -------------------- |
| Id              | uniqueidentifier | PK                   | Định danh danh mục   |
| Name            | nvarchar(200)    | NOT NULL             | Tên danh mục         |
| Description     | nvarchar(500)    |                      | Mô tả                |
| ParentId        | uniqueidentifier | FK                   | ID danh mục cha      |
| DisplayOrder    | int              | NOT NULL, DEFAULT(0) | Thứ tự hiển thị      |
| IsActive        | bit              | NOT NULL, DEFAULT(1) | Trạng thái kích hoạt |
| ImageUrl        | nvarchar(500)    |                      | URL hình ảnh         |
| Slug            | nvarchar(200)    | NOT NULL             | URL thân thiện       |
| MetaTitle       | nvarchar(200)    |                      | Tiêu đề SEO          |
| MetaKeywords    | nvarchar(500)    |                      | Từ khóa SEO          |
| MetaDescription | nvarchar(500)    |                      | Mô tả SEO            |
| CreatedAt       | datetime2        | NOT NULL             | Ngày tạo             |
| CreatedBy       | nvarchar(450)    |                      | Người tạo            |
| ModifiedAt      | datetime2        |                      | Ngày sửa đổi         |
| ModifiedBy      | nvarchar(450)    |                      | Người sửa đổi        |

### 9. Brands

| Column Name  | Data Type        | Constraints          | Description           |
| ------------ | ---------------- | -------------------- | --------------------- |
| Id           | uniqueidentifier | PK                   | Định danh thương hiệu |
| Name         | nvarchar(200)    | NOT NULL             | Tên thương hiệu       |
| Description  | nvarchar(500)    |                      | Mô tả                 |
| LogoUrl      | nvarchar(500)    |                      | URL logo              |
| IsActive     | bit              | NOT NULL, DEFAULT(1) | Trạng thái kích hoạt  |
| DisplayOrder | int              | NOT NULL, DEFAULT(0) | Thứ tự hiển thị       |
| Slug         | nvarchar(200)    | NOT NULL             | URL thân thiện        |
| CreatedAt    | datetime2        | NOT NULL             | Ngày tạo              |
| CreatedBy    | nvarchar(450)    |                      | Người tạo             |
| ModifiedAt   | datetime2        |                      | Ngày sửa đổi          |
| ModifiedBy   | nvarchar(450)    |                      | Người sửa đổi         |

### 10. Orders

| Column Name       | Data Type        | Constraints          | Description            |
| ----------------- | ---------------- | -------------------- | ---------------------- |
| Id                | uniqueidentifier | PK                   | Định danh đơn hàng     |
| OrderNumber       | nvarchar(50)     | NOT NULL             | Số đơn hàng            |
| CustomerId        | uniqueidentifier | FK, NOT NULL         | ID khách hàng          |
| OrderDate         | datetime2        | NOT NULL             | Ngày đặt hàng          |
| OrderStatusId     | int              | NOT NULL             | Trạng thái đơn hàng    |
| ShippingAddressId | uniqueidentifier | FK, NOT NULL         | Địa chỉ giao hàng      |
| BillingAddressId  | uniqueidentifier | FK                   | Địa chỉ thanh toán     |
| PaymentMethodId   | int              |                      | Phương thức thanh toán |
| ShippingMethodId  | int              |                      | Phương thức vận chuyển |
| SubTotal          | decimal(18,2)    | NOT NULL             | Tổng tiền hàng         |
| ShippingCost      | decimal(18,2)    | NOT NULL, DEFAULT(0) | Phí vận chuyển         |
| TaxAmount         | decimal(18,2)    | NOT NULL, DEFAULT(0) | Thuế                   |
| DiscountAmount    | decimal(18,2)    | NOT NULL, DEFAULT(0) | Giảm giá               |
| TotalAmount       | decimal(18,2)    | NOT NULL             | Tổng cộng              |
| Notes             | nvarchar(max)    |                      | Ghi chú                |
| CouponCode        | nvarchar(50)     |                      | Mã giảm giá            |
| CreatedAt         | datetime2        | NOT NULL             | Ngày tạo               |
| CreatedBy         | nvarchar(450)    |                      | Người tạo              |
| ModifiedAt        | datetime2        |                      | Ngày sửa đổi           |
| ModifiedBy        | nvarchar(450)    |                      | Người sửa đổi          |

### 11. OrderItems

| Column Name | Data Type        | Constraints  | Description            |
| ----------- | ---------------- | ------------ | ---------------------- |
| Id          | uniqueidentifier | PK           | Định danh mục đơn hàng |
| OrderId     | uniqueidentifier | FK, NOT NULL | ID đơn hàng            |
| ProductId   | uniqueidentifier | FK, NOT NULL | ID sản phẩm            |
| Quantity    | int              | NOT NULL     | Số lượng               |
| UnitPrice   | decimal(18,2)    | NOT NULL     | Đơn giá                |
| TotalPrice  | decimal(18,2)    | NOT NULL     | Thành tiền             |
| ProductName | nvarchar(200)    | NOT NULL     | Tên sản phẩm           |
| SKU         | nvarchar(100)    |              | Mã SKU                 |
| CreatedAt   | datetime2        | NOT NULL     | Ngày tạo               |

### 12. OrderStatuses

| Column Name  | Data Type     | Constraints | Description          |
| ------------ | ------------- | ----------- | -------------------- |
| Id           | int           | PK          | Định danh trạng thái |
| Name         | nvarchar(50)  | NOT NULL    | Tên trạng thái       |
| Description  | nvarchar(200) |             | Mô tả                |
| DisplayOrder | int           | NOT NULL    | Thứ tự hiển thị      |

### 13. PaymentMethods

| Column Name        | Data Type     | Constraints          | Description             |
| ------------------ | ------------- | -------------------- | ----------------------- |
| Id                 | int           | PK                   | Định danh phương thức   |
| Name               | nvarchar(100) | NOT NULL             | Tên phương thức         |
| Description        | nvarchar(500) |                      | Mô tả                   |
| IsActive           | bit           | NOT NULL, DEFAULT(1) | Trạng thái kích hoạt    |
| DisplayOrder       | int           | NOT NULL             | Thứ tự hiển thị         |
| AdditionalSettings | nvarchar(max) |                      | Cấu hình bổ sung (JSON) |

### 14. ShippingMethods

| Column Name     | Data Type     | Constraints          | Description              |
| --------------- | ------------- | -------------------- | ------------------------ |
| Id              | int           | PK                   | Định danh phương thức    |
| Name            | nvarchar(100) | NOT NULL             | Tên phương thức          |
| Description     | nvarchar(500) |                      | Mô tả                    |
| Price           | decimal(18,2) | NOT NULL             | Giá                      |
| DeliveryTimeMin | int           |                      | Thời gian giao tối thiểu |
| DeliveryTimeMax | int           |                      | Thời gian giao tối đa    |
| IsActive        | bit           | NOT NULL, DEFAULT(1) | Trạng thái kích hoạt     |
| DisplayOrder    | int           | NOT NULL             | Thứ tự hiển thị          |

## 👥 Customer Management Tables

### 15. Customers

| Column Name              | Data Type        | Constraints          | Description                    |
| ------------------------ | ---------------- | -------------------- | ------------------------------ |
| Id                       | uniqueidentifier | PK                   | Định danh khách hàng           |
| UserId                   | nvarchar(450)    | FK                   | ID người dùng (nếu đã đăng ký) |
| FirstName                | nvarchar(100)    | NOT NULL             | Tên                            |
| LastName                 | nvarchar(100)    | NOT NULL             | Họ                             |
| Email                    | nvarchar(256)    | NOT NULL             | Email                          |
| PhoneNumber              | nvarchar(20)     |                      | Số điện thoại                  |
| DateOfBirth              | date             |                      | Ngày sinh                      |
| Gender                   | nvarchar(10)     |                      | Giới tính                      |
| CustomerTypeId           | int              |                      | Loại khách hàng                |
| IsSubscribedToNewsletter | bit              | NOT NULL, DEFAULT(0) | Đăng ký newsletter             |
| CreatedAt                | datetime2        | NOT NULL             | Ngày tạo                       |
| CreatedBy                | nvarchar(450)    |                      | Người tạo                      |
| ModifiedAt               | datetime2        |                      | Ngày sửa đổi                   |
| ModifiedBy               | nvarchar(450)    |                      | Người sửa đổi                  |

### 16. Addresses

| Column Name       | Data Type        | Constraints          | Description                 |
| ----------------- | ---------------- | -------------------- | --------------------------- |
| Id                | uniqueidentifier | PK                   | Định danh địa chỉ           |
| CustomerId        | uniqueidentifier | FK, NOT NULL         | ID khách hàng               |
| FirstName         | nvarchar(100)    | NOT NULL             | Tên                         |
| LastName          | nvarchar(100)    | NOT NULL             | Họ                          |
| AddressLine1      | nvarchar(200)    | NOT NULL             | Địa chỉ dòng 1              |
| AddressLine2      | nvarchar(200)    |                      | Địa chỉ dòng 2              |
| City              | nvarchar(100)    | NOT NULL             | Thành phố                   |
| State             | nvarchar(100)    |                      | Tỉnh/Bang                   |
| PostalCode        | nvarchar(20)     |                      | Mã bưu điện                 |
| CountryId         | int              | NOT NULL             | ID quốc gia                 |
| PhoneNumber       | nvarchar(20)     |                      | Số điện thoại               |
| IsDefaultShipping | bit              | NOT NULL, DEFAULT(0) | Địa chỉ giao hàng mặc định  |
| IsDefaultBilling  | bit              | NOT NULL, DEFAULT(0) | Địa chỉ thanh toán mặc định |
| CreatedAt         | datetime2        | NOT NULL             | Ngày tạo                    |
| CreatedBy         | nvarchar(450)    |                      | Người tạo                   |
| ModifiedAt        | datetime2        |                      | Ngày sửa đổi                |
| ModifiedBy        | nvarchar(450)    |                      | Người sửa đổi               |

### 17. Countries

| Column Name  | Data Type     | Constraints          | Description          |
| ------------ | ------------- | -------------------- | -------------------- |
| Id           | int           | PK                   | Định danh quốc gia   |
| Name         | nvarchar(100) | NOT NULL             | Tên quốc gia         |
| IsoCode      | nvarchar(2)   | NOT NULL             | Mã ISO2              |
| IsoCode3     | nvarchar(3)   |                      | Mã ISO3              |
| IsActive     | bit           | NOT NULL, DEFAULT(1) | Trạng thái kích hoạt |
| DisplayOrder | int           | NOT NULL             | Thứ tự hiển thị      |

### 18. CustomerTypes

| Column Name        | Data Type     | Constraints | Description               |
| ------------------ | ------------- | ----------- | ------------------------- |
| Id                 | int           | PK          | Định danh loại khách hàng |
| Name               | nvarchar(100) | NOT NULL    | Tên loại                  |
| Description        | nvarchar(500) |             | Mô tả                     |
| DiscountPercentage | decimal(5,2)  |             | % giảm giá mặc định       |

## 📦 Inventory & Stock Tables

### 19. Inventory

| Column Name      | Data Type        | Constraints          | Description        |
| ---------------- | ---------------- | -------------------- | ------------------ |
| Id               | uniqueidentifier | PK                   | Định danh kho      |
| ProductId        | uniqueidentifier | FK, NOT NULL         | ID sản phẩm        |
| WarehouseId      | uniqueidentifier | FK, NOT NULL         | ID kho hàng        |
| StockQuantity    | int              | NOT NULL             | Số lượng tồn       |
| ReservedQuantity | int              | NOT NULL, DEFAULT(0) | Số lượng đặt trước |
| CreatedAt        | datetime2        | NOT NULL             | Ngày tạo           |
| CreatedBy        | nvarchar(450)    |                      | Người tạo          |
| ModifiedAt       | datetime2        |                      | Ngày sửa đổi       |
| ModifiedBy       | nvarchar(450)    |                      | Người sửa đổi      |

### 20. InventoryHistory

| Column Name    | Data Type        | Constraints  | Description       |
| -------------- | ---------------- | ------------ | ----------------- |
| Id             | uniqueidentifier | PK           | Định danh lịch sử |
| ProductId      | uniqueidentifier | FK, NOT NULL | ID sản phẩm       |
| WarehouseId    | uniqueidentifier | FK, NOT NULL | ID kho hàng       |
| QuantityChange | int              | NOT NULL     | Thay đổi số lượng |
| QuantityBefore | int              | NOT NULL     | Số lượng trước    |
| QuantityAfter  | int              | NOT NULL     | Số lượng sau      |
| Note           | nvarchar(500)    |              | Ghi chú           |
| ReferenceType  | nvarchar(50)     |              | Loại tham chiếu   |
| ReferenceId    | nvarchar(128)    |              | ID tham chiếu     |
| CreatedAt      | datetime2        | NOT NULL     | Ngày tạo          |
| CreatedBy      | nvarchar(450)    | NOT NULL     | Người tạo         |

### 21. Warehouses

| Column Name  | Data Type        | Constraints          | Description          |
| ------------ | ---------------- | -------------------- | -------------------- |
| Id           | uniqueidentifier | PK                   | Định danh kho hàng   |
| Name         | nvarchar(200)    | NOT NULL             | Tên kho hàng         |
| AddressLine1 | nvarchar(200)    | NOT NULL             | Địa chỉ dòng 1       |
| AddressLine2 | nvarchar(200)    |                      | Địa chỉ dòng 2       |
| City         | nvarchar(100)    | NOT NULL             | Thành phố            |
| State        | nvarchar(100)    |                      | Tỉnh/Bang            |
| PostalCode   | nvarchar(20)     |                      | Mã bưu điện          |
| CountryId    | int              | NOT NULL             | ID quốc gia          |
| PhoneNumber  | nvarchar(20)     |                      | Số điện thoại        |
| Email        | nvarchar(256)    |                      | Email                |
| IsActive     | bit              | NOT NULL, DEFAULT(1) | Trạng thái kích hoạt |
| CreatedAt    | datetime2        | NOT NULL             | Ngày tạo             |
| CreatedBy    | nvarchar(450)    |                      | Người tạo            |
| ModifiedAt   | datetime2        |                      | Ngày sửa đổi         |
| ModifiedBy   | nvarchar(450)    |                      | Người sửa đổi        |

## ⭐ Review & Rating Tables

### 22. ProductReviews

| Column Name        | Data Type        | Constraints          | Description          |
| ------------------ | ---------------- | -------------------- | -------------------- |
| Id                 | uniqueidentifier | PK                   | Định danh đánh giá   |
| ProductId          | uniqueidentifier | FK, NOT NULL         | ID sản phẩm          |
| CustomerId         | uniqueidentifier | FK, NOT NULL         | ID khách hàng        |
| OrderItemId        | uniqueidentifier | FK                   | ID mục đơn hàng      |
| Rating             | int              | NOT NULL             | Điểm đánh giá (1-5)  |
| ReviewText         | nvarchar(max)    |                      | Nội dung đánh giá    |
| Title              | nvarchar(200)    |                      | Tiêu đề đánh giá     |
| IsApproved         | bit              | NOT NULL, DEFAULT(0) | Đã duyệt             |
| IsVerifiedPurchase | bit              | NOT NULL, DEFAULT(0) | Đã xác minh mua hàng |
| CreatedAt          | datetime2        | NOT NULL             | Ngày tạo             |
| CreatedBy          | nvarchar(450)    |                      | Người tạo            |
| ModifiedAt         | datetime2        |                      | Ngày sửa đổi         |
| ModifiedBy         | nvarchar(450)    |                      | Người sửa đổi        |

### 23. ReviewHelpfulness

| Column Name | Data Type        | Constraints  | Description   |
| ----------- | ---------------- | ------------ | ------------- |
| Id          | uniqueidentifier | PK           | Định danh     |
| ReviewId    | uniqueidentifier | FK, NOT NULL | ID đánh giá   |
| CustomerId  | uniqueidentifier | FK, NOT NULL | ID khách hàng |
| IsHelpful   | bit              | NOT NULL     | Có hữu ích    |
| CreatedAt   | datetime2        | NOT NULL     | Ngày tạo      |

## 📢 Marketing Tables

### 24. Discounts

| Column Name           | Data Type        | Constraints          | Description                |
| --------------------- | ---------------- | -------------------- | -------------------------- |
| Id                    | uniqueidentifier | PK                   | Định danh giảm giá         |
| Name                  | nvarchar(200)    | NOT NULL             | Tên chương trình           |
| Description           | nvarchar(500)    |                      | Mô tả                      |
| DiscountType          | int              | NOT NULL             | Loại giảm giá              |
| DiscountValue         | decimal(18,2)    | NOT NULL             | Giá trị giảm giá           |
| MinimumOrderAmount    | decimal(18,2)    |                      | Giá trị đơn hàng tối thiểu |
| MaximumDiscountAmount | decimal(18,2)    |                      | Giảm giá tối đa            |
| StartDate             | datetime2        | NOT NULL             | Ngày bắt đầu               |
| EndDate               | datetime2        |                      | Ngày kết thúc              |
| CouponCode            | nvarchar(50)     |                      | Mã giảm giá                |
| UsesPerCustomer       | int              |                      | Số lần sử dụng/KH          |
| UsesPerCoupon         | int              |                      | Tổng số lần sử dụng        |
| IsActive              | bit              | NOT NULL, DEFAULT(1) | Trạng thái kích hoạt       |
| CreatedAt             | datetime2        | NOT NULL             | Ngày tạo                   |
| CreatedBy             | nvarchar(450)    |                      | Người tạo                  |
| ModifiedAt            | datetime2        |                      | Ngày sửa đổi               |
| ModifiedBy            | nvarchar(450)    |                      | Người sửa đổi              |

### 25. DiscountUsageHistory

| Column Name | Data Type        | Constraints  | Description   |
| ----------- | ---------------- | ------------ | ------------- |
| Id          | uniqueidentifier | PK           | Định danh     |
| DiscountId  | uniqueidentifier | FK, NOT NULL | ID giảm giá   |
| OrderId     | uniqueidentifier | FK, NOT NULL | ID đơn hàng   |
| CustomerId  | uniqueidentifier | FK, NOT NULL | ID khách hàng |
| CreatedAt   | datetime2        | NOT NULL     | Ngày tạo      |

## 💻 Logging & Audit Tables

### 26. AuditLogs

| Column Name | Data Type        | Constraints | Description   |
| ----------- | ---------------- | ----------- | ------------- |
| Id          | uniqueidentifier | PK          | Định danh log |
| UserId      | nvarchar(450)    |             | ID người dùng |
| EntityName  | nvarchar(100)    | NOT NULL    | Tên entity    |
| EntityId    | nvarchar(128)    | NOT NULL    | ID entity     |
| Action      | nvarchar(50)     | NOT NULL    | Hành động     |
| OldValues   | nvarchar(max)    |             | Giá trị cũ    |
| NewValues   | nvarchar(max)    |             | Giá trị mới   |
| ClientIp    | nvarchar(50)     |             | Địa chỉ IP    |
| CreatedAt   | datetime2        | NOT NULL    | Thời gian     |

### 27. ActivityLogs

| Column Name  | Data Type        | Constraints | Description          |
| ------------ | ---------------- | ----------- | -------------------- |
| Id           | uniqueidentifier | PK          | Định danh log        |
| UserId       | nvarchar(450)    |             | ID người dùng        |
| ActivityType | nvarchar(100)    | NOT NULL    | Loại hoạt động       |
| Description  | nvarchar(500)    |             | Mô tả                |
| EntityName   | nvarchar(100)    |             | Tên entity           |
| EntityId     | nvarchar(128)    |             | ID entity            |
| IpAddress    | nvarchar(50)     |             | Địa chỉ IP           |
| UserAgent    | nvarchar(500)    |             | Trình duyệt/thiết bị |
| CreatedAt    | datetime2        | NOT NULL    | Thời gian            |

## 📊 Mối quan hệ chính

1. **Products** ↔ **Categories**: Mỗi sản phẩm thuộc một danh mục
2. **Products** ↔ **Brands**: Mỗi sản phẩm thuộc một thương hiệu
3. **Products** ↔ **ProductImages**: Một sản phẩm có nhiều hình ảnh
4. **Products** ↔ **ProductAttributes**: Một sản phẩm có nhiều thuộc tính
5. **Products** ↔ **Inventory**: Một sản phẩm có nhiều bản ghi tồn kho
6. **Products** ↔ **OrderItems**: Một sản phẩm có thể xuất hiện trong nhiều đơn hàng
7. **Orders** ↔ **OrderItems**: Một đơn hàng có nhiều mục
8. **Orders** ↔ **Customers**: Mỗi đơn hàng thuộc về một khách hàng
9. **Customers** ↔ **Addresses**: Một khách hàng có nhiều địa chỉ
10. **Customers** ↔ **AspNetUsers**: Một khách hàng có thể liên kết với một tài khoản

---
