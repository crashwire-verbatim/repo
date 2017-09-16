===sdrausty's repositories===
sdrausty hosts community repositories from an Android smartphone at
[https://pages.github.com Github Pages.]

https://sdrausty.github.io/repo/ is one of the Termux community repositories hosted at [https://sdrausty.github.io sdrausty.github.io] through [https://pages.github.com Github Pages] at [https://github.com Github.]

You can add this repository by copying and pasting the next three command lines into the Termux window:
<pre>

pkg install apt-transport-https

echo "deb [trusted=yes] https://sdrausty.github.io/repo termux extras" >> $PREFIX/etc/apt/sources.list

pkg update

</pre>

This will allow <code>pkg</code> to access the repo repository at [https://sdrausty.github.io sdrausty.github.io] from within Termux through <code>apt</code> on your portable device. 

At present this repository is set up for diagnostic purposes and your enjoyment. Please comment at https://github.com/sdrausty/repo/issues after adding it to your <code>$PREFIX/etc/apt/sources.list</code> file. To see what your <code>sources.list</code> file contains, type <code>cat $PREFIX/etc/apt/sources.list</code> at the command prompt.

