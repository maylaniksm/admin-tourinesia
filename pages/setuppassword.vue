<template>
    <div>
        <div class="container-fluid">
            <div class="row justify-content-center" style="">
                <div class="col-xl-6 col-lg-6 col-md-6 col-sm-9" style="position: absolute; top: 25%;">
                    <div class="card o-hidden border-3 shadow-lg my-3">
                        <div class="card-body p-0" style="">
                            <div class="p-5">
                                <div class="text-center">
                                    <h1 class="h4 text-gray-900 mb-4">SET UP PASSWORD</h1>
                                </div>
                                <form class="user">
                                    <div class="form-group">
                                        <input type="password" class="form-control form-control-user" id="exampleInputPassword" placeholder="Password Now">
                                    </div>
                                        <div class="form-group">
                                        <input type="password" class="form-control form-control-user" id="exampleInputPassword" placeholder="New Password">
                                    </div>
                                    <div class="form-group">
                                    </div>
                                    <a href="javascript:void(0)" @click="submit" class="btn btn-primary btn-user btn-block">
                                        Confirmation
                                    </a>
                                    <hr>
                                </form>
                                <div class="text-center">
                                    <a class="small" href="#">Back to Login!</a>
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
