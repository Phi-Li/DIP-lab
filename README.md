# DIP-lab
## OpenCV
Version 3.2.0
### Image file reading and writing
- [`imread(filename[, flags])`](https://docs.opencv.org/master/d4/da8/group__imgcodecs.html#ga288b8b3da0892bd651fce07b3bbd3a56)
- [`imwrite(filename, img[, params])`](https://docs.opencv.org/master/d4/da8/group__imgcodecs.html#gabbc7ef1aa2edfaa87772f1202d67e0ce)
### High-level GUI
- [`imshow(winname, mat)`](https://docs.opencv.org/master/d7/dfc/group__highgui.html#ga453d42fe4cb60e5723281a89973ee563)
- [`waitKey([, delay])`](https://docs.opencv.org/master/d7/dfc/group__highgui.html#ga5628525ad33f52eab17feebcfba38bd7)
- [`destroyAllWindows()`](https://docs.opencv.org/master/d7/dfc/group__highgui.html#ga6b7fc1c1a8960438156912027b38f481)
- [`setMouseCallback()`](https://docs.opencv.org/master/d7/dfc/group__highgui.html#ga89e7806b0a616f6f1d502bd8c183ad3e)
### Video I/O
- [`VideoCapture()`](https://docs.opencv.org/master/d8/dfe/classcv_1_1VideoCapture.html#a57c0e81e83e60f36c83027dc2a188e80)
- [`VideoWriter()`](https://docs.opencv.org/master/dd/d9e/classcv_1_1VideoWriter.html#ad59c61d8881ba2b2da22cff5487465b5)
- [`VideoWriter_fourcc(c1, c2, c3, c4)`](https://docs.opencv.org/master/dd/d9e/classcv_1_1VideoWriter.html#afec93f94dc6c0b3e28f4dd153bc5a7f0)
### Miscellaneous Image Transformations
- [`cvtColor(src, code[, dst[, dstCn]])`](https://docs.opencv.org/master/d7/d1b/group__imgproc__misc.html#ga397ae87e1288a81d2363b61574eb8cab)
- [`threshold(src, thresh, maxval, type[, dst])`](https://docs.opencv.org/master/d7/d1b/group__imgproc__misc.html#gae8a4a146d1ca78c626a53577199e9c57)
- [`adaptiveThreshold(src, maxValue, adaptiveMethod, thresholdType, blockSize, C[, dst])`](https://docs.opencv.org/master/d7/d1b/group__imgproc__misc.html#ga72b913f352e4a1b1b397736707afcde3)
### Operations on arrays
- [`flip(src, flipCode[, dst])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#gaca7be533e3dac7feb70fc60635adf441)
- [`add(src1, src2[, dst[, mask[, dtype]]])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#ga10ac1bfb180e2cfda1701d06c24fdbd6)
- [`addWeighted(src1, alpha, src2, beta, gamma[, dst[, dtype]])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#gafafb2513349db3bcff51f54ee5592a19)
- [`subtract(src1, src2[, dst[, mask[, dtype]]])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#gaa0f00d98b4b5edeaeb7b8333b2de353b)
- [`mulitply(src1, src2[, dst[, scale[, dtype]]])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#ga979d898a58d7f61c53003e162e7ad89f)
- [`bitwise_not(src[, dst[, mask]])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#ga0002cf8b418479f4cb49a75442baee2f)
- [`bitwise_and(src1, src2[, dst[, mask]])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#ga60b4d04b251ba5eb1392c34425497e14)
- [`minMaxLoc(src[, mask])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#gab473bf2eb6d14ff97e89b355dac20707)
- [`absdiff(src1, src2[, dst])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#ga6fef31bc8c4071cbc114a758a2b79c14)
- [`inRange(src, lowerb, upperb[, dst])`](https://docs.opencv.org/master/d2/de8/group__core__array.html#ga48af0ab51e36436c5d04340e036ce981)
### Drawing Functions
- [`line(img, pt1, pt2, color[, thickness[, lineType[, shift]]])`](https://docs.opencv.org/master/d6/d6e/group__imgproc__draw.html#ga7078a9fae8c7e7d13d24dac2520ae4a2)
- [`circle(img, center, radius, color[, thickness[, lineType[, shift]]])`](https://docs.opencv.org/master/d6/d6e/group__imgproc__draw.html#gaf10604b069374903dbd0f0488cb43670)
- [`rectangle(img, pt1, pt2, color[, thickness[, lineType[, shift]]])`](https://docs.opencv.org/master/d6/d6e/group__imgproc__draw.html#ga07d2f74cadcf8e305e810ce8eed13bc9)
- [`ellipse()`](https://docs.opencv.org/master/d6/d6e/group__imgproc__draw.html#ga28b2267d35786f5f890ca167236cbc69)
- [`putText(img, text, org, fontFace, fontScale, color[, thickness[, lineType[, bottomLeftOrigin]]])`](https://docs.opencv.org/master/d6/d6e/group__imgproc__draw.html#ga5126f47f883d730f633d74f07456c576)
- [`polylines(img, pts, isClosed, color[, thickness[, lineType[, shift]]])`](https://docs.opencv.org/master/d6/d6e/group__imgproc__draw.html#ga444cb8a2666320f47f09d5af08d91ffb)
### Geometric Image Transformations
- [`resize(src, dsize[, dst[, fx[, fy[, interpolation]]]])`](https://docs.opencv.org/master/da/d54/group__imgproc__transform.html#ga47a974309e9102f5f08231edc7e7529d)
- [`getRotationMatrix2D(center, angle, scale)`](https://docs.opencv.org/master/da/d54/group__imgproc__transform.html#gafbbc470ce83812914a70abfb604f4326)
- [`warpAffine(src, M, dsize[, dst[, flags[, borderMode[, borderValue]]]])`](https://docs.opencv.org/master/da/d54/group__imgproc__transform.html#ga0203d9ee5fcd28d40dbc4a1ea4451983)
- [`getAffineTransform(src, dst)`](https://docs.opencv.org/master/da/d54/group__imgproc__transform.html#ga8f6d378f9f8eebb5cb55cd3ae295a999)
- [`getPerspectiveTransform(src, dst)`](https://docs.opencv.org/master/da/d54/group__imgproc__transform.html#ga8c1ae0e3589a9d77fffc962c49b22043)
- [`warpPerspective(src, M, dsize[, dst[, flags[, borderMode[, borderValue]]]])`](https://docs.opencv.org/master/da/d54/group__imgproc__transform.html#gaf73673a7e8e18ec6963e3774e6a94b87)
### Histograms
- [`calcHist(images, channels, mask, histSize, ranges[, hist[, accumulate]])`](https://docs.opencv.org/master/d6/dc7/group__imgproc__hist.html#ga4b2b5fd75503ff9e6844cc4dcdaed35d)
- [`equalizeHist(src[, dst])`](https://docs.opencv.org/master/d6/dc7/group__imgproc__hist.html#ga7e54091f0c937d49bf84152a16f76d6e)
### Image Filtering
- [`filter2D(src, ddepth, kernel[, dst[, anchor[, delta[, borderType]]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#ga27c049795ce870216ddfb366086b5a04)
- [`blur(src, ksize[, dst[, anchor[, borderType]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#ga8c45db9afe636703801b0b2e440fce37)
- [`boxFilter(src, ddepth, ksize[, dst[, anchor[, normalize[, borderType]]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#gad533230ebf2d42509547d514f7d3fbc3)
- [`medianBlur(src, ksize[, dst])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#ga564869aa33e58769b4469101aac458f9)
- [`GaussianBlur(src, ksize, sigmaX[, dst[, sigmaY[, borderType]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#gaabe8c836e97159a9193fb0b11ac52cf1)
- [`Laplacian(src, ddepth[, dst[, ksize[, scale[, delta[, borderType]]]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#gad78703e4c8fe703d479c1860d76429e6)
- [`Sobel(src, ddepth, dx, dy[, dst[, ksize[, scale[, delta[, borderType]]]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#gacea54f142e81b6758cb6f375ce782c8d)
- [`erode(src, kernel[, dst[, anchor[, iterations[, borderType[, borderValue]]]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#gaeb1e0c1033e3f6b891a25d0511362aeb)
- [`dilate(src, kernel[, dst[, anchor[, iterations[, borderType[, borderValue]]]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#ga4ff0f3318642c4f469d0e11f242f3b6c)
- [`morphologyEx(src, op, kernel[, dst[, anchor[, iterations[, borderType[, borderValue]]]]])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#ga67493776e3ad1a3df63883829375201f)
- [`getStructuringElement(shape, ksize[, anchor])`](https://docs.opencv.org/master/d4/d86/group__imgproc__filter.html#gac342a1bb6eabf6f55c803b09268e36dc)
### Object Detection
- [`matchTemplate(image, templ, method[, result[, mask]])`](https://docs.opencv.org/master/df/dfb/group__imgproc__object.html#ga586ebfb0a7fb604b35a23d85391329be)
## NumPy
### Array creation routines
- [`numpy.zeros(shape, dtype=float, order='C')`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.zeros.html)
- [`numpy.ones(shape, dtype=None, order='C')`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.ones.html)
- [`numpy.array(object, dtype=None, copy=True, order='K', subok=False, ndmin=0)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.array.html)
- [`numpy.arange([start, ]stop, [step, ]dtype=None)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.arange.html)
### Statistics
- [`numpy.histogram(a, bins=10, range=None, normed=False, weights=None, density=None)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.histogram.html)
### Array manipulation routines
- [`numpy.hstack(tup)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.hstack.html)
- [`numpy.hsplit(ary, indices_or_sections)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.hsplit.html)
### Discrete Fourier Transform ([`numpy.fft`](https://docs.scipy.org/doc/numpy/reference/routines.fft.html))
- [`numpy.fft.fft2(a, s=None, axes=(-2, -1), norm=None)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.fft.fft2.html)
- [`numpy.fft.fftshift(x, axes=None)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.fft.fftshift.html)
- [`numpy.fft.ifftshift(x, axes=None)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.fft.ifftshift.html)
- [`numpy.fft.ifft2(a, s=None, axes=(-2, -1), norm=None)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.fft.ifft2.html)
### Mathematical functions
- [`numpy.log(x, /, out=None, *, where=True, casting='same_kind', order='K', dtype=None, subok=True[, signature, extobj]) = <ufunc 'log'>`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.log.html)
- [`numpy.absolute(x, /, out=None, *, where=True, casting='same_kind', order='K', dtype=None, subok=True[, signature, extobj]) = <ufunc 'absolute'>`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.absolute.html)
- [`numpy.sum(a, axis=None, dtype=None, out=None, keepdims=<class numpy._globals._NoValue>)`](https://docs.scipy.org/doc/numpy/reference/generated/numpy.sum.html)
## Matplotlib
- [`matplotlib.pyplot.hist(x, bins=None, range=None, density=None, weights=None, cumulative=False, bottom=None, histtype='bar', align='mid', orientation='vertical', rwidth=None, log=False, color=None, label=None, stacked=False, normed=None, hold=None, data=None, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.hist.html)
- [`matplotlib.pyplot.show(*args, **kw)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.show.html)
- [`matplotlib.pyplot.plot(*args, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.plot.html)
- [`matplotlib.pyplot.xlim(*args, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.xlim.html)
- [`matplotlib.pyplot.legend(*args, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.legend.html)
- [`matplotlib.pyplot.subplot(*args, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.subplot.html)
- [`matplotlib.pyplot.imshow(X, cmap=None, norm=None, aspect=None, interpolation=None, alpha=None, vmin=None, vmax=None, origin=None, extent=None, shape=None, filternorm=1, filterrad=4.0, imlim=None, resample=None, url=None, hold=None, data=None, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.imshow.html)
- [`matplotlib.pyplot.title(s, *args, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.title.html)
- [`matplotlib.pyplot.xticks(*args, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.xticks.html)
- [`matplotlib.pyplot.yticks(*args, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.yticks.html)
- [`matplotlib.pyplot.suptitle(*args, **kwargs)`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.suptitle.html)
