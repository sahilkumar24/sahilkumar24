window.requestAnimFrame function () {

return (

window.requestAnimationFrame 11 window.webkitRequestAnimationFrame || window.mozRequestAnimationFrame || window.oRequestAnimationFrame || window.msRequestAnimationFrame || window.setTimeout(callback);

function (callback) {

):

function init(elemid) ( let canvas document.getElementById(elemid).

c = canvas.getContext("2d"),

w= (canvas.width = window.innerWidth),

h = (canvas.height = window.innerHeight);

c.fillStyle "rgba(30, 30, 30, 1)"; c.fillRect(0, e, w, h): return { c: c, canvas: canvas }:

window.onload = function () { let c = init("canvas").c,

canvas = init("canvas").canvas,

w = (canvas.width = window.innerWidth),

h = (canvas.height = window.innerHeight).
