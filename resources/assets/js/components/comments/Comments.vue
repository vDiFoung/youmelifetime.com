<template>
    <div>
        <div class="post-comments mt-5">
            <div class="container">
                <div class="row">
                    <div class="comments col-md-9" id="comments">
                        <h3 class="mb-2">Title</h3>
                        <!-- comment -->
                        <div class="comment mb-2 row">
                            <div class="comment-avatar col-md-1 col-sm-2 text-center pr-1">
                                <a href=""><img class="mx-auto rounded-circle img-fluid"
                                                src="http://demos.themes.guide/bodeo/assets/images/users/m103.jpg"
                                                alt="avatar"></a>
                            </div>
                            <div class="comment-content col-md-11 col-sm-10">
                                <h6 class="small comment-meta"><a href="#">admin</a> Today, 2:38</h6>
                                <div class="comment-body">
                                    <p>
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                                        eiusmod <a href>http://wwwwww.com</a> tempor incididunt ut
                                        labore et dolore magna aliqua. Ut enim ad minim veniam, quis
                                        nostrud exercitation ullamco laboris nisi ut aliquip ex ea
                                        commodo.
                                        <br>
                                        <a href="" class="text-right small"><i class="ion-reply"></i>
                                            Reply</a>
                                    </p>
                                </div>
                            </div>

                            <!-- reply is indented -->
                            <div class="comment-reply col-md-11 offset-md-1 col-sm-10 offset-sm-2">
                                <div class="row">
                                    <div class="comment-avatar col-md-1 col-sm-2 text-center pr-1">
                                        <a href=""><img class="mx-auto rounded-circle img-fluid"
                                                        src="http://demos.themes.guide/bodeo/assets/images/users/m101.jpg"
                                                        alt="avatar"></a>
                                    </div>
                                    <div class="comment-content col-md-11 col-sm-10 col-12">
                                        <h6 class="small comment-meta"><a href="#">phildownney</a>
                                            Today, 12:31</h6>
                                        <div class="comment-body">
                                            <p>Really?? Consectetur adipisicing elit, sed do eiusmod
                                                tempor incididunt ut labore et dolore magna aliqua. Ut
                                                enim ad minim veniam, quis nostrud exercitat.
                                                <br>
                                                <a href="" class="text-right small"><i
                                                        class="ion-reply"></i> Reply</a>
                                            </p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <!-- /reply is indented -->
                        </div>
                        <!-- /comment -->
                        <!-- comment -->
                        <div class="comment mb-2 row">
                            <div class="comment-avatar col-md-1 col-sm-2 text-center pr-1">
                                <a href=""><img class="mx-auto rounded-circle img-fluid"
                                                src="http://demos.themes.guide/bodeo/assets/images/users/w102.jpg"
                                                alt="avatar"></a>
                            </div>
                            <div class="comment-content col-md-11 col-sm-10">
                                <h6 class="small comment-meta"><a href="#">maslarino</a> Yesterday, 5:03
                                    PM</h6>
                                <div class="comment-body">
                                    <p>Sit amet, consectetur adipisicing elit, sed do eiusmod tempor
                                        incididunt ut labore et dolore magna aliqua. Ut enim ad minim
                                        veniam, quis nostrud exercitation ullamco laboris nisi ut
                                        aliquip ex ea commodo.
                                        <br>
                                        <a href="" class="text-right small"><i class="ion-reply"></i>
                                            Reply</a>
                                    </p>
                                </div>
                            </div>
                        </div>
                        <!-- /comment -->
                        <p class="text-center"><a href="">Xem thêm</a></p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
  export default {
    name: 'comments',
  }
</script>

<style scoped lang="scss">

</style>