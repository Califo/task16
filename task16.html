/**
 * aqiData，存储用户输入的空气指数数据
 * 示例格式：
 * aqiData = {
 *    "北京": 90,
 *    "上海": 40
 * };
 */
var aqiData = {};
var cityInput = document.getElementById('aqi-city-input');
var cityValue = document.getElementById('aqi-value-input');
var btn = document.getElementById('add-btn');
var table = document.getElementById('aqi-table')

/**
 * 从用户输入中获取数据，向aqiData中增加一条数据
 * 然后渲染aqi-list列表，增加新增的数据
 */
function addAqiData() {
	var strCity = cityInput.value.trim();
	var value = cityValue.value.trim();
	
	//此处有关正则表达式
	var regCity = /^[\u4E00-\u9FA5a-zA-Z]+$/;//中英文字符
	var regValue = /^[\d]+$/;//整数
	
	var flagCity = true;
	var flagValue = true;
	if(!regCity.test(strCity)){
		alert('必须为中英文字符');
		flagCity = false;
	}
	if(!regValue.test(value)){
		alert('必须为整数');
		flagValue = false;
	}
	if(flagCity && flagValue){
		aqiData[strCity] = value;
	}
}

/**
 * 渲染aqi-table表格
 */
function renderAqiList() {
	var tr = '<tr><td>城市</td><td>空气质量</td><td>操作</td></tr>';
	
	for(var city in aqiData){
		tr += '<tr><td>'+ city +'</td><td>'+aqiData[city]+'</td><td><button>删除</button></td></tr>';
	}
	table.innerHTML = tr;
}

/**
 * 点击add-btn时的处理逻辑
 * 获取用户输入，更新数据，并进行页面呈现的更新
 */
function addBtnHandle() {
	
  addAqiData();
  renderAqiList();
}

/**
 * 点击各个删除按钮的时候的处理逻辑
 * 获取哪个城市数据被删，删除数据，更新表格显示
 */
function delBtnHandle(evt) {
  // do sth.
	//evt.path  阅读 事件冒泡 相关文档
	delete aqiData[evt.path[2].firstChild.innerHTML];
  renderAqiList();
}

function init() {

  // 在这下面给add-btn绑定一个点击事件，点击时触发addBtnHandle函数
	btn.addEventListener('click',addBtnHandle);
  // 想办法给aqi-table中的所有删除按钮绑定事件，触发delBtnHandle函数
	table.addEventListener('click',delBtnHandle);
}

init();
