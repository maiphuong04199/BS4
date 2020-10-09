<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!--BootStrap CDN-->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <!--BootStrap-->
    <link rel="stylesheet" type="text/css" href="bootstrap4/css/bootstrap.css">
    <link rel="stylesheet" type="text/css" href="bootstrap4/js/bootstrap.js">

    <link rel="stylesheet" href="style.css">
    <title>BootStrap</title>
</head>

<body>
    <h1>BOOTSTRAP 4</h1>
    <h3>- Bootstrap là framework bao gồm các HTML, CSS và JavaScript phổ biến để phát triển các trang web chuẩn responsive.
        <br>- Bootstrap 4 là phiên bản mới nhất của Bootstrap, với các thành phần mới, định kiểu và khả năng phản hồi nhanh hơn.
        <br>- ƯU ĐIỂM:
        <H4> + Dễ sử dụng.
            <br>+ Các tính năng đáp ứng: điều chỉnh phù hợp với mọi thiết bị như điện thoại, máy tính.
            <br> + Phương pháp ưu tiên thiết bị di động.
            <br> + Khả năng tương thích với tất cả các trình duyệt hiện đại như chrome, firefox, opera,...
        </H4>
    </h3>
    <div style="margin-bottom: 100px;"></div>
    <div>
        <!--Container-->
        <div>
            <div class="container bg-primary text-white p-3">
                <p style="font-size: 120px;">.container</p>
            </div>
            <div class="container-fluid bg-danger text-white p-3">
                <p style="font-size: 120px;">.container-fluid</p>
            </div>
        </div>

        <!--Grid System-->
        <div class="grid-system" style="font-weight: bolder; text-align: center;">
            <div class="row bg-warning border" style="margin-top: 100px;">
                <div class="col" style="background-color: green;">.col-1</div>
                <div class="col">.col-1</div>
                <div class="col" style="background-color: green;">.col-1</div>
                <div class="col">.col-1</div>
                <div class="col" style="background-color: green;">.col-1</div>
                <div class="col">.col-1</div>
                <div class="col" style="background-color: green;">.col-1</div>
                <div class="col">.col-1</div>
                <div class="col" style="background-color: green;">.col-1</div>
                <div class="col">.col-1</div>
                <div class="col" style="background-color: green;">.col-1</div>
                <div class="col">.col-1</div>
            </div>
            <div class="row bg-warning border">
                <div class="col-4" style="background-color: green;">.col-4</div>
                <div class="col-4">.col-4</div>
                <div class="col-4" style="background-color: green;">.col-4</div>
            </div>
            <div class="row bg-warning border">
                <div class="col-4" style="background-color: green;">.col-4</div>
                <div class="col-8">.col-8</div>
            </div>
            <div class="row bg-warning border">
                <div class="col-6" style="background-color: green;">.col-6</div>
                <div class="col-6">.col-6</div>
            </div>
            <div class="row bg-warning border">
                <div class="col-12">.col-12</div>
            </div>
        </div>
        <!--typography-->
        <div class="container">
            <h1>Đây là <small>Small</small></h1>
            <h1>Đây là <mark>Mark</mark></h1>
            <h1>Đây là <abbr title="Tôi ở đây">abbr</abbr></h1>
            <h1>Đây là
                <blockquote>blockquote</blockquote>
            </h1>
            <h1>Đây là <code>CODE</code></h1>
            <h1>Đây là <kbd>kbd</kbd></h1>
        </div>
        <!--Color-->
        <div class="cotainer color">
            <div class="container text_color">
                <h1>Text Color</h1>
                <h3 class="text-primary">primary</h3>
                <h3 class="text-success">success</h3>
                <h3 class="text-info">info</h3>
                <h3 class="text-warning">warning</h3>
                <h3 class="text-danger">danger</h3>
                <h3 class="text-secondary">secondary</h3>
                <h3 class="text-dark">dark</h3>
                <h3 class="text-light">light</h3>
            </div>
            <div class="container bg_color">
                <h1>Background Color</h1>
                <h3 class="bg-primary">.bg - primary</h3>
                <h3 class="bg-success">.bg - success</h3>
                <h3 class="bg-info">.bg - info</h3>
                <h3 class="bg-warning">.bg - warning</h3>
                <h3 class="bg-danger">.bg - danger</h3>
                <h3 class="bg-secondary">.bg - secondary</h3>
                <h3 class="bg-dark">.bg - dark</h3>
                <h3 class="bg-light">.bg - light</h3>
            </div>
        </div>

        <!--Table-->
        <div class="container Table">
            <div class="container table">
                <h2>Table</h2>
                <table class="table">
                    <thead>
                        <tr>
                            <th>STT</th>
                            <th>Họ và Tên</th>
                            <th>Lớp</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td>Mai Anh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>Mai Linh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>Mai Sơn</td>
                            <td>D17CN</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="container table_striped">
                <h2>Table Striped</h2>
                <table class="table table-striped">
                    <thead>
                        <tr>
                            <th>STT</th>
                            <th>Họ và Tên</th>
                            <th>Lớp</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td>Mai Anh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>Mai Linh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>Mai Sơn</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>4</td>
                            <td>Mai Yên</td>
                            <td>D17CN</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="container table_bordered">
                <h2>Table Bordered</h2>
                <table class="table table-bordered">
                    <thead>
                        <tr>
                            <th>STT</th>
                            <th>Họ và Tên</th>
                            <th>Lớp</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td>Mai Anh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>Mai Linh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>Mai Sơn</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>4</td>
                            <td>Mai Yên</td>
                            <td>D17CN</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="container table_hover">
                <h2>Table Hover</h2>
                <table class="table table-hover">
                    <thead>
                        <tr>
                            <th>STT</th>
                            <th>Họ và Tên</th>
                            <th>Lớp</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td>Mai Anh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>Mai Linh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>Mai Sơn</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>4</td>
                            <td>Mai Yên</td>
                            <td>D17CN</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="container table_dark">
                <h2>Table Dark</h2>
                <table class="table table-dark">
                    <thead>
                        <tr>
                            <th>STT</th>
                            <th>Họ và Tên</th>
                            <th>Lớp</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td>Mai Anh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>Mai Linh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>Mai Sơn</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>4</td>
                            <td>Mai Yên</td>
                            <td>D17CN</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="container table_borderless">
                <h2>Table Borderless</h2>
                <table class="table table-borderless">
                    <thead>
                        <tr>
                            <th>STT</th>
                            <th>Họ và Tên</th>
                            <th>Lớp</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>1</td>
                            <td>Mai Anh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>2</td>
                            <td>Mai Linh</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>3</td>
                            <td>Mai Sơn</td>
                            <td>D17CN</td>
                        </tr>
                        <tr>
                            <td>4</td>
                            <td>Mai Yên</td>
                            <td>D17CN</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="container table_contextual">
                <h2>Table Contextual</h2>
                <table class="table">
                    <thead>
                        <tr>
                            <th>Tên</th>
                            <th>Lớp</th>
                            <th>Email</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Default</td>
                            <td>D17CN</td>
                            <td>def@somemail.com</td>
                        </tr>
                        <tr class="table-primary">
                            <td>Primary</td>
                            <td>D17CN</td>
                            <td>pri@example.com</td>
                        </tr>
                        <tr class="table-success">
                            <td>Success</td>
                            <td>D17CN</td>
                            <td>suc@example.com</td>
                        </tr>
                        <tr class="table-danger">
                            <td>Danger</td>
                            <td>D17CN</td>
                            <td>dan@example.com</td>
                        </tr>
                        <tr class="table-info">
                            <td>Info</td>
                            <td>D17CN</td>
                            <td>info@example.com</td>
                        </tr>
                        <tr class="table-warning">
                            <td>Warning</td>
                            <td>D17CN</td>
                            <td>war@example.com</td>
                        </tr>
                        <tr class="table-active">
                            <td>Active</td>
                            <td>D17CN</td>
                            <td>act@example.com</td>
                        </tr>
                        <tr class="table-secondary">
                            <td>Secondary</td>
                            <td>D17CN</td>
                            <td>sec@example.com</td>
                        </tr>
                        <tr class="table-light">
                            <td>Light</td>
                            <td>D17CN</td>
                            <td>lig@example.com</td>
                        </tr>
                        <tr class="table-dark text-dark">
                            <td>Dark</td>
                            <td>D17CN</td>
                            <td>dark@example.com</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="container table_small">
                <h2>Small Table</h2>
                <table class="table table-bordered table-sm">
                    <thead>
                        <tr>
                            <th>Firstname</th>
                            <th>Lastname</th>
                            <th>Email</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>John</td>
                            <td>Doe</td>
                            <td>john@example.com</td>
                        </tr>
                        <tr>
                            <td>Mary</td>
                            <td>Moe</td>
                            <td>mary@example.com</td>
                        </tr>
                        <tr>
                            <td>July</td>
                            <td>Dooley</td>
                            <td>july@example.com</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="container table_responsive">
                <h2>Responsive Table</h2>
                <div class="table-responsive">
                    <table class="table table-bordered table-dark">
                        <thead>
                            <tr>
                                <th>#</th>
                                <th>Firstname</th>
                                <th>Lastname</th>
                                <th>Age</th>
                                <th>City</th>
                                <th>Country</th>
                                <th>Sex</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                                <th>Example</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>1</td>
                                <td>Anna</td>
                                <td>Pitt</td>
                                <td>35</td>
                                <td>New York</td>
                                <td>USA</td>
                                <td>Female</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                                <td>Yes</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
        <!--Images-->
        <div>
            <div class="container img_rounded">
                <h2>Image Rounded</h2>
                <img src="image/logo.jpg" class="rounded" alt="Logo" width="304" height="236">
            </div>
            <div class="container img_circle">
                <h2>Image Rounded</h2>
                <img src="image/logo.jpg" class="rounded-circle" alt="Logo" width="304" height="236">
            </div>
            <div class="container img_thumbnail">
                <h2>Image Rounded</h2>
                <img src="image/logo.jpg" class="img-thumbnail" alt="Logo" width="304" height="236">
            </div>
        </div>
        <br>
        <!--jumbotron-->
        <div class="container jumbotron">
            <h1>Bootstrap Jumbotron</h1>
            <p>Bootstrap is the most popular HTML, CSS...</p>
        </div>
        <!--Alert-->
        <div>
            <div class="container alert" style="font-size: 20px;">
                <h2>Alerts</h2>
                <div class="alert alert-success">
                    <strong>.alert-uccess</strong>
                </div>
                <div class="alert alert-info">
                    <strong>.alert-info</strong>
                </div>
                <div class="alert alert-warning">
                    <strong>.alert-warning</strong>
                </div>
                <div class="alert alert-danger">
                    <strong>.alert-danger</strong>
                </div>
                <div class="alert alert-primary">
                    <strong>.alert-primary</strong>
                </div>
                <div class="alert alert-secondary">
                    <strong>.alert-secondary</strong>
                </div>
                <div class="alert alert-dark">
                    <strong>.alert-dark</strong>
                </div>
                <div class="alert alert-light">
                    <strong>.alert-light</strong>
                </div>
            </div>
            <div class="container alert_link">
                <h2>Alert Links</h2>
                <div class="alert alert-success">
                    <a href="#" class="alert-link">Success Link</a>.
                </div>
                <div class="alert alert-info">
                    <a href="#" class="alert-link">Info Link</a>.
                </div>
                <div class="alert alert-warning">
                    <a href="#" class="alert-link">Warning Link</a>.
                </div>
                <div class="alert alert-danger">
                    <a href="#" class="alert-link">Danger Link</a>.
                </div>
                <div class="alert alert-primary">
                    <a href="#" class="alert-link">Primary Link</a>.
                </div>
                <div class="alert alert-secondary">
                    <a href="#" class="alert-link">Secondary Link</a>.
                </div>
                <div class="alert alert-dark">
                    <a href="#" class="alert-link">Dark Link</a>.
                </div>
                <div class="alert alert-light">
                    <a href="#" class="alert-link">Light Link</a>.
                </div>
            </div>
            <div class="container alert_closing">
                <h2>Closin Alerts </h2>
                <div class="alert alert-success alert-dismissible">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Success!</strong>
                </div>
                <div class="alert alert-info alert-dismissible">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Info!</strong>
                </div>
                <div class="alert alert-warning alert-dismissible">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Warning!</strong>
                </div>
                <div class="alert alert-danger alert-dismissible">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Danger!</strong>
                </div>
                <div class="alert alert-primary alert-dismissible">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Primary!</strong>
                </div>
                <div class="alert alert-secondary alert-dismissible">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Secondary!</strong>
                </div>
                <div class="alert alert-dark alert-dismissible">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Dark!</strong>
                </div>
                <div class="alert alert-light alert-dismissible">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Light!</strong>
                </div>
            </div>
            <div class="container alert_animated">
                <h2>Animated Alerts</h2>
                <div class="alert alert-success alert-dismissible fade show">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Success!</strong>
                </div>
                <div class="alert alert-info alert-dismissible fade show">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Info!</strong>
                </div>
                <div class="alert alert-warning alert-dismissible fade show">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Warning!</strong>
                </div>
                <div class="alert alert-danger alert-dismissible fade show">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Danger!</strong>
                </div>
                <div class="alert alert-primary alert-dismissible fade show">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Primary!</strong>
                </div>
                <div class="alert alert-secondary alert-dismissible fade show">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Secondary!</strong>
                </div>
                <div class="alert alert-dark alert-dismissible fade show">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Dark!</strong>
                </div>
                <div class="alert alert-light alert-dismissible fade show">
                    <button type="button" class="close" data-dismiss="alert">&times;</button>
                    <strong>Light!</strong>
                </div>
            </div>
        </div>
        <!--Botton-->
        <div class="container Button">
            <div class="container button_styles">
                <h2>Button Styles</h2>
                <button type="button" class="btn">.btn</button>
                <button type="button" class="btn btn-primary">,btn-primary</button>
                <button type="button" class="btn btn-secondary">.btn-secondary</button>
                <button type="button" class="btn btn-success">.btn-success</button>
                <button type="button" class="btn btn-info">.btn-info</button>
                <button type="button" class="btn btn-warning">.btn-warning</button>
                <button type="button" class="btn btn-danger">.btn-danger</button>
                <button type="button" class="btn btn-dark">.btn-ark</button>
                <button type="button" class="btn btn-light">.btn-light</button>
                <button type="button" class="btn btn-link">.btn-ink</button>
            </div>
            <div class="container button_outline">
                <h2>Button Outline</h2>
                <button type="button" class="btn btn-outline-primary">.btn-outline-primary</button>
                <button type="button" class="btn btn-outline-secondary">.btn-outline-secondary</button>
                <button type="button" class="btn btn-outline-success">.btn-outline-success</button>
                <button type="button" class="btn btn-outline-info">.btn-outline-info</button>
                <button type="button" class="btn btn-outline-warning">.btn-outline-warning</button>
                <button type="button" class="btn btn-outline-danger">.btn-outline-danger</button>
                <button type="button" class="btn btn-outline-dark">.btn-outline-dark</button>
                <button type="button" class="btn btn-outline-light text-dark">.btn-outline-light</button>
            </div>
            <div class="container button_size">
                <h2>Button Sizes</h2>
                <button type="button" class="btn btn-primary btn-lg">.btn-lg</button>
                <button type="button" class="btn btn-primary btn-md">.btn-md</button>
                <button type="button" class="btn btn-primary btn-sm">.btn-sm</button>
            </div>
            <div class="container block_level_button">
                <h2>Block Level Buttons</h2>
                <button type="button" class="btn btn-primary btn-block">btn-primary btn-block</button>
                <button type="button" class="btn btn-success btn-block">btn-success btn-block</button>
                <br>
                <h2>Large Block Level Buttons</h2>
                <button type="button" class="btn btn-primary btn-lg btn-block">btn-primary btn-lg btn-block</button>
                <button type="button" class="btn btn-success btn-lg btn-block">btn-success btn-lg btn-block</button>
                <br>
                <h2>Small Block Level Buttons</h2>
                <button type="button" class="btn btn-primary btn-sm btn-block">btn-primary btn-sm btn-block</button>
                <button type="button" class="btn btn-success btn-sm btn-block">btn-success btn-sm btn-block</button>
            </div>
            <div class="container button_active_disabled">
                <h2>Active/Disabled Button</h2>
                <button type="button" class="btn btn-success">btn-success</button>
                <button type="button" class="btn btn-success active">btn-success active</button>
                <button type="button" class="btn btn-warning disabled">btn-warning disabled</button>
            </div>
            <div class="container button_spinner">
                <h2>Spinner Buttons</h2>
                <button class="btn btn-dark">
          <span class="spinner-border spinner-border-sm"></span>
        </button>
                <button class="btn btn-dark">
          <span class="spinner-border spinner-border-lg"></span>
        </button>
            </div>
            <div class="container button_group_row">
                <h2>Button Group</h2>
                <div class="btn-group">
                    <button type="button" class="btn btn-danger">btn1</button>
                    <button type="button" class="btn btn-danger">btn2</button>
                    <button type="button" class="btn btn-danger">btn3</button>
                </div>
            </div>
            <div class="container button_group_column">
                <h2>Vertical Button Group</h2>
                <div class="btn-group-vertical">
                    <button type="button" class="btn btn-danger">btn1</button>
                    <button type="button" class="btn btn-danger">btn2</button>
                    <button type="button" class="btn btn-danger">btn3</button>
                </div>
            </div>
            <div class="container button_split_downdrop">
                <h2>Split Buttons</h2>
                <div class="btn-group">
                    <button type="button" class="btn btn-primary">Slipt Button</button>
                    <button type="button" class="btn btn-primary dropdown-toggle dropdown-toggle-split" data-toggle="dropdown">
            <span class="caret"></span>
          </button>
                    <div class="dropdown-menu">
                        <a class="dropdown-item" href="#">btn1</a>
                        <a class="dropdown-item" href="#">btn2</a>
                    </div>
                </div>
            </div>
        </div>

        <!--Badge-->
        <div class="cotainer Badge">
            <div class="container badge">
                <h2>Contextual Badges</h2>
                <span class="badge badge-primary">badge-primary</span>
                <span class="badge badge-secondary">badge-secondary</span>
                <span class="badge badge-success">badge-success</span>
                <span class="badge badge-danger">badge-danger</span>
                <span class="badge badge-warning">badge-warning</span>
                <span class="badge badge-info">badge-info</span>
                <span class="badge badge-light">badge-light</span>
                <span class="badge badge-dark">badge-dark</span>
            </div>
            <div class="container badge_inside">
                <h2>Badge inside a Button</h2>
                <button type="button" class="btn btn-danger">
              BUTTON <span class="badge badge-light">Badge</span>
            </button>
            </div>
        </div>

        <!--Progress-->
        <div class="container Progress">
            <h2>Progress Bar</h2>
            <div class="progress" style="height: 50px;">
                <div class="progress-bar" style="width:80%; height: 50px;">80% progerss-bar</div>
            </div>
            <br>
            <div class="progress" style="height: 50px;">
                <div class="progress-bar bg-dark" style="width:90%; height: 50px;">90% progress-bar bg-dark</div>
            </div>
            <br>
            <div class="progress" style="height: 50px;">
                <div class="progress-bar progress-bar-striped progress-bar-animated" style="width:95%">progress-bar-animated</div>
            </div>
            <br>
            <div class="progress" style="height: 50px;">
                <div class="progress-bar bg-success" style="width:40%">
                    Success
                </div>
                <div class="progress-bar bg-warning" style="width:10%">
                    Warning
                </div>
                <div class="progress-bar bg-danger" style="width:20%">
                    Danger
                </div>
            </div>
        </div>

        <!--Spinner-->
        <div class="container Spinner">
            <div class="container spinner_color">
                <h2>Colored Spinners</h2>
                <div class="spinner-border text-muted"></div>
                <div class="spinner-border text-primary"></div>
                <div class="spinner-border text-success"></div>
                <div class="spinner-border text-info"></div>
                <div class="spinner-border text-warning"></div>
                <div class="spinner-border text-danger"></div>
                <div class="spinner-border text-secondary"></div>
                <div class="spinner-border text-dark"></div>
                <div class="spinner-border text-light"></div>
            </div>
            <div class="container growing_spinner">
                <h2>Growing Spinners</h2>
                <div class="spinner-grow text-muted"></div>
                <div class="spinner-grow text-primary"></div>
                <div class="spinner-grow text-success"></div>
                <div class="spinner-grow text-info"></div>
                <div class="spinner-grow text-warning"></div>
                <div class="spinner-grow text-danger"></div>
                <div class="spinner-grow text-secondary"></div>
                <div class="spinner-grow text-dark"></div>
                <div class="spinner-grow text-light"></div>
            </div>
        </div>

        <!--Pagination-->
        <div class="cotainer Pagination">
            <div class="container pagination_basic">
                <h2>Pagination</h2>
                <p>Default:</p>
                <ul class="pagination">
                    <li class="page-item"><a class="page-link" href="#">Previous</a></li>
                    <li class="page-item"><a class="page-link" href="#">1</a></li>
                    <li class="page-item"><a class="page-link" href="#">2</a></li>
                    <li class="page-item"><a class="page-link" href="#">3</a></li>
                    <li class="page-item"><a class="page-link" href="#">Next</a></li>
                </ul>
                <p>Large: .pagination-lg</p>
                <ul class="pagination pagination-lg">
                    <li class="page-item disabled"><a class="page-link" href="#">Previous</a></li>
                    <li class="page-item"><a class="page-link" href="#">1</a></li>
                    <li class="page-item active"><a class="page-link" href="#">2</a></li>
                    <li class="page-item"><a class="page-link" href="#">3</a></li>
                    <li class="page-item"><a class="page-link" href="#">Next</a></li>
                </ul>
                <p>Small: .pagination-sm</p>
                <ul class="pagination pagination-sm">
                    <li class="page-item"><a class="page-link" href="#">Previous</a></li>
                    <li class="page-item"><a class="page-link" href="#">1</a></li>
                    <li class="page-item"><a class="page-link" href="#">2</a></li>
                    <li class="page-item"><a class="page-link" href="#">3</a></li>
                    <li class="page-item"><a class="page-link" href="#">Next</a></li>
                </ul>
            </div>
            <br>
            <div class="container breadcrumbs">
                <h2>Breadcrumbs</h2>
                <ul class="breadcrumb">
                    <li class="breadcrumb-item"><a href="#">HTML</a></li>
                    <li class="breadcrumb-item"><a href="#">CSS</a></li>
                    <li class="breadcrumb-item"><a href="#">JavaScript</a></li>
                    <li class="breadcrumb-item active">BootStrap4</li>
                </ul>
            </div>
        </div>

        <!--List Group-->
        <div class="container List_group">
            <div class="container Basic">
                <h2>List Group</h2>
                <div class="list-group">
                    <a href="#" class="list-group-item list-group-item-action">.list-group-item-action</a>
                    <a href="#" class="list-group-item disabled">.disabled</a>
                    <a href="#" class="list-group-item">.list-group-item</a>
                </div>
            </div>
            <br>
            <div class="container LG_Flush">
                <h2>Flush / Remove Borders</h2>
                <ul class="list-group list-group-flush">
                    <li class="list-group-item">First item</li>
                    <li class="list-group-item">Second item</li>
                    <li class="list-group-item">Third item</li>
                    <li class="list-group-item">Fourth item</li>
                </ul>
            </div>
            <br>
            <div class="container LG_horizontal">
                <h2>Horizontal List Groups</h2>
                <ul class="list-group list-group-horizontal">
                    <li class="list-group-item">First item</li>
                    <li class="list-group-item">Second item</li>
                    <li class="list-group-item">Third item</li>
                    <li class="list-group-item">Fourth item</li>
                </ul>
            </div>
            <br>
            <div class="container Contextual_Classes">
                <h2>Contextual Classes</h2>
                <ul class="list-group">
                    <li class="list-group-item list-group-item-success">list-group-item-success</li>
                    <li class="list-group-item list-group-item-secondary">list-group-item-secondary</li>
                    <li class="list-group-item list-group-item-info">list-group-item-info</li>
                    <li class="list-group-item list-group-item-warning">list-group-item-warning</li>
                    <li class="list-group-item list-group-item-danger">list-group-item-danger</li>
                    <li class="list-group-item list-group-item-primary">list-group-item-primary</li>
                    <li class="list-group-item list-group-item-dark">list-group-item-dark</li>
                    <li class="list-group-item list-group-item-light">list-group-item-light</li>
                </ul>
            </div>
            <br>
            <div class="container LG_Link">
                <h2>Linked Items With Contextual Classes</h2>
                <div class="list-group">
                    <a href="#" class="list-group-item list-group-item-action">Action item</a>
                    <a href="#" class="list-group-item list-group-item-action list-group-item-success">Success item</a>
                    <a href="#" class="list-group-item list-group-item-action list-group-item-secondary">Secondary item</a>
                    <a href="#" class="list-group-item list-group-item-action list-group-item-info">Info item</a>
                    <a href="#" class="list-group-item list-group-item-action list-group-item-warning">Warning item</a>
                    <a href="#" class="list-group-item list-group-item-action list-group-item-danger">Danger item</a>
                    <a href="#" class="list-group-item list-group-item-action list-group-item-primary">Primary item</a>
                    <a href="#" class="list-group-item list-group-item-action list-group-item-dark">Dark item</a>
                    <a href="#" class="list-group-item list-group-item-action list-group-item-light">Light item</a>
                </div>
            </div>
            <br>
            <div class="container mt-3">
                <h2>List Group With Badges</h2>
                <ul class="list-group">
                    <li class="list-group-item d-flex justify-content-between align-items-center">
                        HTML
                        <span class="badge badge-primary badge-pill">badge</span>
                    </li>
                    <li class="list-group-item d-flex justify-content-between align-items-center">
                        CSS
                        <span class="badge badge-primary badge-pill">badge</span>
                    </li>
                    <li class="list-group-item d-flex justify-content-between align-items-center">
                        BOOTSTRAP4
                        <span class="badge badge-primary badge-pill">badge</span>
                    </li>
                </ul>
            </div>
        </div>

        <!--Card-->
        <div class="container basic_card">

            <div class="card">
                <h1>Card</h1>
                <div class="card-header">Header</div>
                <div class="card-body">Basic card</div>
                <div class="card-footer">Footer</div>
                <br>
            </div>
            <div class=" card Contextual_Cards">
                <h2>Contextual Cards</h2>
                <div class="card bg-primary text-white">
                    <div class="card-body">Primary card</div>
                </div>
                <div class="card bg-success text-white">
                    <div class="card-body">Success card</div>
                </div>
                <div class="card bg-info text-white">
                    <div class="card-body">Info card</div>
                </div>
                <div class="card bg-warning text-white">
                    <div class="card-body">Warning card</div>
                </div>
                <div class="card bg-danger text-white">
                    <div class="card-body">Danger card</div>
                </div>
                <div class="card bg-secondary text-white">
                    <div class="card-body">Secondary card</div>
                </div>
                <div class="card bg-dark text-white">
                    <div class="card-body">Dark card</div>
                </div>
                <div class="card bg-light text-dark">
                    <div class="card-body">Light card</div>
                </div>
            </div>
            <div class="card title_link">
                <div class="card-body">
                    <h2 class="card-title">Card title</h2>
                    <a href="#" class="card-link">Card link</a>
                    <a href="#" class="card-link">Another link</a>
                </div>
            </div>
            <div class="card image_card" style="width:400px">
                <img class="card-img-top" src="image/logo.jpg" alt="Card image">
                <div class="card-body">
                    <h4 class="card-title">Mai Phương</h4>
                    <p class="card-text">Some example text.</p>
                    <a href="#" class="btn btn-primary">See Profile</a>
                </div>
            </div>
            <div class="card img_overlay" style="width:500px">
                <img class="card-img-top" src="image/avatar.jpg" alt="Card image">
                <div class="card-img-overlay">
                    <h4 class="card-title">Mai Phương</h4>
                    <p class="card-text">Some example text.</p>
                    <a href="#" class="btn btn-primary">See Profile</a>
                </div>
            </div>
            <div class="card-columns">
                <div class="card bg-primary">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the first card</p>
                    </div>
                </div>
                <div class="card bg-warning">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the second card</p>
                    </div>
                </div>
                <div class="card bg-success">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the third card</p>
                    </div>
                </div>
                <div class="card bg-danger">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the fourth card</p>
                    </div>
                </div>
                <div class="card bg-light">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the fifth card</p>
                    </div>
                </div>
                <div class="card bg-info">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the sixth card</p>
                    </div>
                </div>
            </div>
            <div class="card-deck">
                <div class="card bg-primary">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the first card</p>
                    </div>
                </div>
                <div class="card bg-warning">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the second card</p>
                    </div>
                </div>
                <div class="card bg-success">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the third card</p>
                    </div>
                </div>
                <div class="card bg-danger">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the fourth card</p>
                    </div>
                </div>
            </div>
            <div class="card-group">
                <div class="card bg-primary">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the first card</p>
                    </div>
                </div>
                <div class="card bg-warning">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the second card</p>
                    </div>
                </div>
                <div class="card bg-success">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the third card</p>
                    </div>
                </div>
                <div class="card bg-danger">
                    <div class="card-body text-center">
                        <p class="card-text">Some text inside the fourth card</p>
                    </div>
                </div>
            </div>
        </div>

        <!--Nav-->
        <div>
            <div class="container nav_basic">
                <h2>Nav Basic</h2>
                <ul class="nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link disabled" href="#">Disabled</a>
                    </li>
                </ul>
            </div>
            <div class="container">
                <h2>Vertical Nav</h2>
                <ul class="nav flex-column">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link1</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link2</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link3</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link disabled" href="#">Disabled</a>
                    </li>
                </ul>
            </div>
            <div class="container">
                <h2>Navigation Tabs</h2>
                <ul class="nav nav-tabs">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Active</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link1</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#">Dropdown</a>
                        <div class="dropdown-menu">
                            <a class="dropdown-item" href="#">Link 1</a>
                            <a class="dropdown-item" href="#">Link 2</a>
                            <a class="dropdown-item" href="#">Link 3</a>
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link disabled" href="#">Disabled</a>
                    </li>
                </ul>
            </div>
            <div class="container">
                <h2>Toggleable Tabs</h2>
                <br>
                <!-- Nav tabs -->
                <ul class="nav nav-tabs" role="tablist">
                    <li class="nav-item">
                        <a class="nav-link active" data-toggle="tab" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" data-toggle="tab" href="#menu1">Menu 1</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" data-toggle="tab" href="#menu2">Menu 2</a>
                    </li>
                </ul>

                <!-- Tab panes -->
                <div class="tab-content">
                    <div id="home" class="container tab-pane active"><br>
                        <h3>HOME</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                    </div>
                    <div id="menu1" class="container tab-pane fade"><br>
                        <h3>Menu 1</h3>
                        <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                    </div>
                    <div id="menu2" class="container tab-pane fade"><br>
                        <h3>Menu 2</h3>
                        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.</p>
                    </div>
                </div>
            </div>
        </div>

        <!--Navbar-->
        <div class="container nav_bar">
            <div class="navbar_basic">
                <h2>Basic Navbar</h2>
                <nav class="navbar navbar-expand-sm bg-light">

                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 1</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 2</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 3</a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="navbar_vertical">
                <h2>Vertical Navbar</h2>
                <nav class="navbar bg-light">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 1</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 2</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 3</a>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="navbar_center">
                <h2>Centered Navbar</h2>
                <nav class="navbar navbar-expand-sm bg-light justify-content-center">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 1</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 2</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link 3</a>
                        </li>
                    </ul>
                </nav>
                <br>
            </div>
            <div class="navbar_color">
                <h2>Colored Navbar</h2>
                <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
                    <ul class="navbar-nav">
                        <li class="nav-item active">
                            <a class="nav-link" href="#">Active</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Link</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link disabled" href="#">Disabled</a>
                        </li>
                    </ul>
                </nav>
            </div>

        </div>

    </div>






</body>

</html>
