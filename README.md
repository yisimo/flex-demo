# flex-demo
flexdemo 弹性布局
<h2>一、容器的6个属性,设置在容器上</h2>
			<section>
				<h4>1、flex-direction属性决定项目的排列方向</h4>
				<h4>2、flex-wrap属性决定项目是否换行</h4>
				<h4>3、flex-flow属性是flex-direction和flex-wrap的简写形式，默认值是 row和nowrap</h4>
				<h4>4、justify-content属性定义了项目在主轴上的对齐方式</h4>
				<h4>5、align-items属性定义了项目在交叉轴上的对齐方式</h4>
				<h4>6、align-content属性定义了多根轴线与交叉轴的对齐方式，如果只有一根轴线则不起作用</h4>
			</section>
<h2>二、项目的6个属性,设置在项目上</h2>
			<section>
				<h4>1、order属性定义项目的排序，数值越小越靠前，默认值是0</h4>
				<h4>2、flex-grow属性定义项目的放大比例，默认值为0（即如果存在剩余空间也不放大）</h4>
				<h4>3、flex-shrink属性定义项目的缩小比例，默认值为1（即如果空间不足，该项目将缩小）</h4>
				<h4>4、flex-basis属性定义了在分配多余空间时，项目占据的主轴空间，默认值是auto,即项目原本的大小</h4>
				<h4>5、flex是flex-grow、flex-shrink、flex-basis的缩写形式，默认值为0 1 auto,后两个属性可选</h4>
				<h4>6、align-self属性允许单个项目有与其他项目不一样的对齐方式，可覆盖align-items的属性。默认值为auto,表示继承父元素的align-items属性，如果没有父元素，等同于stretch。该属性除了auto外，其余属性与align-items属性完全一致</h4>
				</section>
