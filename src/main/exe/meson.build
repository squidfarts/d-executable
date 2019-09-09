###################################################################################
#                                                                                 #
# NAME: src/main/meson.build                                                      #
#                                                                                 #
# AUTHOR: Michael Brockus.                                                        #
#                                                                                 #
# CONTACT: <mailto:michael@squidfarts.com>                                        #
#                                                                                 #
# NOTICES:                                                                        #
#                                                                                 #
# License: Apache 2.0 :http://www.apache.org/licenses/LICENSE-2.0                 #
#                                                                                 #
###################################################################################



exe_src = [ 'main.d' ]



exe_main = executable('exe', 
    sources: [ exe_src ],
    include_directories: exe_dir,
    install: true)



test('Test exe', exe_main)