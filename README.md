# CI_Image_manipulation_methods
Image Manipulation Methods in CodeIgniter
dependency:<br />
must initialize image library <strong>image_lib</strong><br />
<code>$this->load->library('image_lib');</code>
<div>
<h4>use:</h4>
<h5>for cropping:</h5>
<code>$this->crop($img_full_path, $img_file_name, $width, $height, $prefix, $delimiter);</code>
<h5>for resizing:</h5>
<code>$this->resize($this->upload->data(), $height, $prefix, $delimiter);</code>
<h6>It's important to set as first param of method to be data obj of current upload</h6>
</div>
