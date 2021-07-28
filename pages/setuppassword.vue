<template>
    <div class="container-fluid">
        <div class="row justify-content-center" style="margin: 0 25%">
            <div class="col-xl-10 col-lg-12 col-md-9" style="margin: 10%">
                <div class="card o-hidden border-3 shadow-lg my-3">
                    <div class="card-body p-0">
                        <div class="row">
                            <div class="col-lg-12">
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
    </div>
</template>
<script>
export default{
    layout: 'login_layouts'
}
</script>

