# linux_hfs_in_c
##### 一个基于ANSI C编写的，基于http协议的文件服务器，只能工作于linux平台，它支持分块文件传输及文件上传功能。
##### 我编写这个程序主要是为了让我的树莓派来当作文件共享服务器使用，日常操作只需要通过浏览器而不是命令行。
##### 这个项目仅一个文件，没有第三方库，所有的数据结构和算法都是定制的。另外，这个服务器实现了所谓的 arena allocator 来做全局内存管理。mime.txt 是文件后缀与mime类型的映射文件，可以根据需要自由增减，程序重启后生效。
##### --------------------------------------------------------------------------------------------------------------------------------------------------------
##### a http file list server written in ANSI C, only for linux platform. supports chunked data transfer and file upload.
##### I write this file to serve my raspberrypi as a file shared server, all daily work would be done on web browser, not a cmd.
##### this server's is only one file, no 3rd-parties, all data structures and algorithm are all customized. also, this server implements the arena allocator to do the global memory management. mime.txt is a mapping file to do the mapping from the file extension to mime, you can add or remove lines to fit your own need, and it will be worked when server restarted.

![image](https://github.com/user-attachments/assets/111423c5-b510-4035-8ef9-1b16d1afd413)
