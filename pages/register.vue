<template>
    <div class="container-fluid">
        <div class="row justify-content-center" style="margin: 0 25%">
            <div class="col-xl-10 col-lg-12 col-md-9">
                <div class="card o-hidden border-3 shadow-lg my-3">
                    <div class="card-body p-0">
                        <div class="row">
                            <div class="col-lg-12">
                                <div class="p-5">
                                    <div class="text-center">
                                        <h1 class="h4 text-gray-900 mb-4">REGISTER</h1>
                                    </div>
                                    <form class="user">
                                         <div class="form-group">
                                            <input type="text" class="form-control form-control-user" id="exampleInputName" placeholder="Name">
                                        </div>
                                        <div class="form-group">
                                            <input type="number" class="form-control form-control-user" id="exampleInputPhoneNumber" placeholder="Phone Number">
                                        </div>
                                        <div class="form-group">
                                            <input type="email" class="form-control form-control-user" id="exampleInputEmail" aria-describedby="emailHelp" placeholder="Email Address">
                                        </div>
                                        <div class="form-group">
                                            <input type="password" class="form-control form-control-user" id="exampleInputPassword" placeholder="Password">
                                        </div>
                                         <div class="form-group">
                                            <input type="password" class="form-control form-control-user" id="exampleInputPassword" placeholder="Re-Password">
                                        </div>
                                        <div class="form-group">
                                            <div class="custom-control custom-checkbox small">
                                                <input type="checkbox" class="custom-control-input" id="customCheck">
                                                <label class="custom-control-label" for="customCheck">Remember Me</label>
                                            </div>
                                        </div>
                                        <a href="javascript:void(0)" @click="submit" class="btn btn-primary btn-user btn-block">
                                            Register
                                        </a>
                                        <hr>
                                    </form>
                                    <div class="text-center">
                                        <a class="small" href="#">Back to Login!</a>
                                    </div>
                                    <hr>
                                    
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default{
    layout: 'login_layouts'
}
</script>

