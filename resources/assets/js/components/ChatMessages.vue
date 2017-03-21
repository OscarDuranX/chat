<template>
    <div class="direct-chat-msg">
        <div class="direct-chat-info clearfix">
            <span class="direct-chat-name pull-left">Alexander Pierce</span>
            <span class="direct-chat-timestamp pull-right">23 Jan 2:00 pm</span>
        </div>
        <!-- /.direct-chat-info -->
        <img class="direct-chat-img" src="img/user1-128x128.jpg" alt="Message User Image"><!-- /.direct-chat-img -->
        <div class="direct-chat-text">
            {{ message.message }}
        </div>
        <!-- /.direct-chat-text -->
    </div>

</template>
<style>
</style>
<script>
    export default{
      props: ['messages']
    }
</script>
